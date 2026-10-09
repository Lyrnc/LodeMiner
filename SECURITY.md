# Security

If you find a security problem in LodeMiner (something that could let someone else take over a rig, steal
mining time or credentials, or make the miner send shares or fees somewhere it shouldn't), please don't open a
public issue. Report it privately instead:

- On this page, open **Security > Report a vulnerability**. Only you and the maintainer can see that report.

Please include the LodeMiner version, your Windows version, GPU and driver, what you did, and what happened.
I'll reply as soon as I can and credit you in the release notes if you like.

For everything else (crashes, wrong numbers, a pool that doesn't work) a normal issue is fine.

Always download LodeMiner from this repository's Releases page and compare the SHA-256 checksum in the release
notes with `certutil -hashfile lodeminer.exe SHA256`. Copies from anywhere else may not be genuine.
