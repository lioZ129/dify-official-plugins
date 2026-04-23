# Privacy Policy

This plugin does not collect, store, or share user personal data by itself.

## Data Processed by the Plugin

To provide model inference, the plugin sends requests from Dify to the HPC-AI API endpoint. These requests may include:

- User prompts and conversation messages submitted to the selected model
- Model parameters configured in Dify
- The HPC-AI API key configured as the model provider credential

The plugin does not persist prompts, responses, or API keys outside Dify's normal plugin runtime and credential storage mechanisms.

## Third-Party Service

Model requests are processed by HPC-AI through the configured API endpoint:

https://api.hpc-ai.com/inference/v1

For information about HPC-AI's privacy practices, please refer to:

https://www.hpc-ai.com/agreement/privacy

## Contact

For plugin source code and maintenance information, see:

https://github.com/lioZ129/dify-official-plugins/tree/community/hpc-ai-provider-source/models/hpc_ai
