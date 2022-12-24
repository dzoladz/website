# TO-DO
- [ ] Add `rel=me` [docs](https://indiewebify.me/validate-rel-me/)

# Troubleshooting

## failed to resolve output
When trying to launch the server, it says **“Error: from config: failed to resolve output format “WebAppManifest” from site config”**.

Solution:
- Temporarily remove the “WebAppManifest”, “redirects”, “headers” output types from `config.yaml` under the config folder
- Run the following command: `hugo mod clean && hugo mod tidy`
- Check that hugo now runs OK with `hugo server` and then add the output types back into`config.yaml`.
