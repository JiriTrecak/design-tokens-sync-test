# Supernova <> Figma Tokens example repository

This repository automatically syncs [Figma Tokens](https://docs.tokens.studio/) through GitHub action to [Supernova.io](https://supernova.io) when token data change and is a good example of full automated synchronization between Figma Tokens and Supernova. 

The synchronization is done through GitHub action that runs every time a new token file (or files) is commited into this repository. It uses [Supernova CLI](https://github.com/Supernova-Studio/cli) to facilitate the synchronization routine. 

- To configure automated sync for yourself, follow the tutorial
- To see what data are being synchronized, visit the [`tokens.json`](https://github.com/JiriTrecak/design-tokens-sync-test/blob/main/single-file-sync/tokens.json) file
- To see the Figma Tokens <> Supernova mapping, explore the [`supernova.settings.json`](https://github.com/JiriTrecak/design-tokens-sync-test/blob/main/single-file-sync/supernova.settings.json) file



