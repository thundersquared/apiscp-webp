# ApisCP Yarn Provider

This is a drop-in provider for [ApisCP](https://apiscp.com/) that installs library and tools for the WebP graphics format.

## Installation

```
cd /usr/local/apnscp/resources/playbooks
git clone https://github.com/thundersquared/apiscp-webp.git addins/apiscp-webp
ansible-playbook addin.yml --extra-vars=addin=apiscp-webp
```

## Usage

`cwebp` and similar commands will be available and ready to use in user `PATH`. To learn more about available tools, please see [Downloading and Installing WebP](https://developers.google.com/speed/webp/download).

## Contributing

Submit a PR and have fun!
