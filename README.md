# Spore PNG Decoder - .NET Core
A Spore PNG Decoder in .NET Core, written by [emd](https://github.com/emd4600), with minor edits by Kyle.

This is a console app that reads a Spore PNG file, and outputs the Spore data contained within it.

For most Spore assets, the data will contain two parts - the Pollen Metadata (asset name, description, tags, author, ID, parent asset, etc...), and the Spore Model XML (parts/rigblocks, paints, etc...). For adventures, the data must be processed seperately by an [adventure decoder](https://github.com/Spore-Community/Adventure-Decoder).

Darkspore assets and certain overcomplex assets (where the data does not fit into the PNG) are not supported. If you find any other assets that cannot be decoded with this app, please [submit an issue](https://github.com/Spore-Community/PNG-Decoder-NetCore/issues/new), and include the PNG itself, as we'd like to take a look.

While this app does work, it is mostly provided for reference purposes. Feel free to take a look at the code and modify it. Please credit emd4600 (https://github.com/emd4600) as the author.

*Not associated with or endorsed by Electronic Arts or Maxis.*
