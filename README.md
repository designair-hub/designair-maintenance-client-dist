# Designair Maintenance Client · stable releases

Public distribution channel for **Designair Maintenance Agent**. The private source repository is maintained separately; WordPress sites do not need a GitHub token to receive stable updates.

Download [`jarvis-agent.zip` from the latest stable release](https://github.com/designair-hub/designair-maintenance-client-dist/releases/latest) and install it through WordPress → Plugins → Add New → Upload Plugin. The ZIP contains the `jarvis-agent/` plugin directory.

The installed plugin checks this repository for stable semantic version releases and verifies the ZIP against GitHub's SHA-256 digest before installation. Automatic updates remain a WordPress administrator choice.

Stable packages are built and tested by the private source repository's release workflow on `main`. Version numbers must be incremented to publish a new stable package; existing stable versions are not replaced. Repository source archives are not installable runtime releases.

Current stable version: **v0.0.3**. Settings are available under WordPress → Settings → Designair Maintenance Agent. PHP 8.1+, HTTPS and pretty WordPress REST permalinks are required for paired diagnostics. The central controller also supports agent-free public HTTPS monitoring.
