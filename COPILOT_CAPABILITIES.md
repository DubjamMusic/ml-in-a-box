# GitHub Copilot Capabilities for ai-toolkit-ml-box

## What GitHub Copilot Can Do With This Repository

### Script Maintenance
- Update package versions in `ml_in_a_box.sh` scripts
- Add or remove ML framework dependencies
- Fix installation script bugs and edge cases
- Optimize installation order for faster setup

### Documentation
- Update README files with new package versions
- Maintain software compatibility matrices
- Document breaking changes between Ubuntu versions
- Generate installation troubleshooting guides

### Testing & Validation
- Validate script syntax and shell compatibility
- Check for deprecated package versions
- Verify CUDA/cuDNN compatibility matrices
- Test script execution in containerized environments

### Version Management
- Track upstream package updates
- Identify security vulnerabilities in dependencies
- Update Node.js, Python, and ML framework versions
- Sync version tables between READMEs and installation scripts

### Security
- Scan for vulnerabilities in Python packages
- Check for insecure download URLs or deprecated GPG keys
- Validate SSL certificates and package signatures
- Review CUDA/driver compatibility for security patches

## Common Tasks

### Adding a New Package
1. Update the package list in the appropriate Ubuntu version's `ml_in_a_box.sh`
2. Add package details to the README software table
3. Include license information in the licenses section
4. Test installation compatibility with existing packages

### Updating Package Versions
1. Identify outdated packages via security scans or release notes
2. Update version numbers in installation script
3. Update version numbers in README documentation
4. Test for breaking changes or dependency conflicts

### Supporting New Hardware
1. Research driver and CUDA requirements for new GPU models
2. Update or create new Ubuntu version directory if needed
3. Document hardware compatibility in main README
4. Test installation on target hardware configuration
