# Apex Cache Builder

**cf-sf-apex-cache-builder**

    Builds and caches Apex-related artifacts to optimize deployments.

* **Inputs**:
    * **cache-key**: Unique key for caching artifacts.

Usage Example:

    - name: Build Apex Cache
      uses: ghcr.io/itfulcrum/cf-sf-apex-cache-builder@latest
      with:
      cache-key: "apex-build-cache"
