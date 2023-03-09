# Public CD of SMPTE ST 2131

## General

_This repository is *public*._

Please consult [CONTRIBUTING.md](./CONTRIBUTING.md), [CONFIDENTIALITY.md](./CONFIDENTIALITY.md), [LICENSE.md](./LICENSE.md) and
[PATENTS.md](./PATENTS.md) for important notices.

Please report issues via the repo [Issue Tracker](https://github.com/SMPTE/st2131/issues) or at [31fs-chair@smpte.org](mailto:31fs-chair@smpte.org)

## Public Committee Draft (PCD) Notice

The following elements are made available for a public review period ending no earlier than 2023-09-10, and no later than 2024-03-10:

* [PCD SMPTE ST 2131](https://github.com/SMPTE/st2131/blob/main/31FS-PCD-ST-2131-ADM-in-MXF.pdf)
* [Element a - Example BW64 PCM+ADM WAV file](https://github.com/SMPTE/st2131/blob/main/31FS-PCD-ST-2131a-ADM-in-MXF-2022-12-07.wav.zip)
* [Element b - Example frame-wrapped MXF file created from Element a](https://github.com/SMPTE/st2131/blob/main/31FS-PCD-ST-2131b-ADM-in-MXF-2022-12-07.mxf.zip)

## Details

Public CD of SMPTE ST 2131 - Mapping Audio Definition Model (ADM) and other audio metadata RIFF Chunks to MXF

Public Committee Draft was approved February 23, 2023 and posted to GitHub on 2023-03-10

Audio Definition Model (ADM) metadata is specified in Recommendation ITU-R BS.2076. It provides an open, common metadata model that can describe channel-, object-, and scene-based audio to enable immersive and interactive experiences for broadcasting and cinema. In many workflows (particularly for post-produced audio content) the ADM metadata is carried in BW64 files along with PCM audio (Recommendation ITU-R BS.2088).

SMPTE ST 2131 defines a mechanism for mapping audio metadata RIFF Chunks to MXF files (many audio files are made from RIFF Chunks, including BW64 files). It defines additional MXF support specifically for the mapping and labeling of ADM metadata. This enables use cases such as augmenting TV MXF files with ADM metadata and easy lossless conversion of BW64 files to/from MXF. It also provides the foundation for an IMF Plug-in for adding ADM-described content to Interoperable Master Format (IMF) Compositions (being drafted as SMPTE ST 2067-204).

A Public Committee Draft of SMPTE ST 2131, and sample MXF file, is being provided for review on GitHub <link> for at least six months from 2023-03-10. Developers are encouraged to implement the design and provide feedback via GitHub to improve the document and to increase interoperability between implementations.
