# Brihat Kirti media handoff

Brihat Kirti puts an approved image or video here for a few minutes, so Instagram (or Threads) can fetch it from a public https link. It then removes it once the platform has its own copy.

- Files live at `m/<sha256>.<ext>`. The name is the file's SHA-256, so the link is fixed before the post is approved, and Kirti checks the bytes served here match the approved file before posting.
- Only Kirti writes here, using a token limited to this one repository. Don't add files by hand.
- Served by GitHub Pages at https://manishbrihat.github.io/kirti-media/
