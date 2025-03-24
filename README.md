# Apex Cache Builder

    This repository contain GitHub Action designed to execute Salesforce Apex Test classes and creates mapping for class vs test classes. The action is packaged as a Docker container and provides a specialized function.
    
**cf-sf-apex-cache-builder**

    Builds and caches Apex-related artifacts to optimize deployments.

* **Inputs**:
    * **cache-key**: Unique key for caching artifacts.

Usage Example:

    - name: Build Apex Cache
      uses: ghcr.io/cloudfulcrum-ai/cf-sf-apex-cache-builder@latest
      with:
      cache-key: "apex-build-cache"

## Installation & Usage

To use these GitHub Actions, ensure that your repository has:

* A .github/workflows/ directory for defining workflows.
* Necessary Salesforce authentication secrets configured in GitHub Actions.

## Contributing

Feel free to submit pull requests to improve existing actions or add new functionality.

## License

This project is licensed under the MIT License.
