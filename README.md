# AWS Infrastructure Specification (AWS-IS)

A deterministic infrastructure specification language for generating consistent Infrastructure as Code across multiple IaC tools.

## Project Goal

AWS Infrastructure Specification aims to solve the fragmentation and inconsistency issues in Infrastructure as Code by providing a unified specification format that can deterministically generate identical infrastructure configurations across multiple IaC tools including Terraform, CloudFormation, Pulumi, and AWS CDK.

The core principle is **determinism**: given the same AWS-IS specification, the system will always produce functionally identical infrastructure regardless of the target IaC tool or generation timestamp.

## Vision

- **Single Source of Truth**: Define infrastructure once in a clear, declarative specification
- **Tool Agnostic**: Generate consistent output for any supported IaC tool
- **Deterministic**: Identical specifications produce identical infrastructure every time
- **AI Compatible**: Designed for integration with AI code generators like Claude Code and Kiro

## Use Cases

- **Multi-team Organizations**: Enable teams to use their preferred IaC tools while maintaining consistency
- **Migration Scenarios**: Seamlessly migrate between IaC tools without infrastructure drift
- **AI-Powered Development**: Provide consistent specifications for AI tools to generate infrastructure
- **Compliance & Governance**: Ensure infrastructure patterns comply with organizational standards
- **Educational**: Learn infrastructure concepts without being tied to specific tool syntax

## 🤝 Contributing

We welcome contributions from the community! Please see our [Contributing Guide](CONTRIBUTING.md) for details on how to get started.

### Development Setup
```bash
git clone https://github.com/your-org/aws-infrastructure-spec
cd aws-infrastructure-spec
npm install
npm run build
npm test
```

### Areas for Contribution
- AWS service definitions and mappings
- IaC tool output generators
- Validation rules and policies
- Documentation and examples
- Testing and quality assurance

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

---

**Note**: This project is in early development. The specification format and API are subject to change. We recommend following the project for updates and contributing feedback during the design phase.
