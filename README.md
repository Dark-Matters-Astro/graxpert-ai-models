# GraXpert AI models for manual installation

This repository provides [GraXpert's](https://graxpert.com) ai models for manual installation released under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1). To install, extract the released .zip files into the appropriate folder (platform dependent). Generally, the path schema is as follows:
`<base_path>/GraXpert/GraXpert/<model_folder_name>/<model_version>/`
where path entries enclosed in arrows `<>` denote placeholders you need to replace appropriately. `<model_version>` is always a three-tuple in the format `x.y.z`

## Valid names for `<model_folder_name>`
- `bge-ai-models`
- `denoise-ai-models`
- `deconvolution-object-ai-models`
- `deconvolution-stars-ai-models`

## Valid names for `<base_path>`
- Windows: `%localappdata`, e.g., `C:\Users\<your_username>\AppData\Local\`
- Linux: `/home/<your_username>/.local/share/`
- MacOS: `/Users/<your_username>/Library/Application Support/`

## Examples for valid, completely resolved paths
- Windows: `C:\Users\schmelly\AppData\Local\GraXpert\GraXpert\deconvolution-object-ai-models\1.0.1`
- Linux: `/home/schmelly/.local/share/GraXpert/GraXpert/deconvolution-object-ai-models/1.0.1`
- MacOS: `/Users/schmelly/Library/Application Support/GraXpert/GraXpert/deconvolution-object-ai-models/1.0.1`
