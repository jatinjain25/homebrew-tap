# jatinjain25/homebrew-tap

Homebrew formulae for [rankme](https://github.com/jatinjain25/rankme).

```sh
brew install jatinjain25/tap/rankme
rankme
```

`rankme` measures the AI coding work already on your machine and asks before it publishes
anything. That confirmation is read from a real terminal, so run it from a shell rather than
from CI or an agent's shell tool.

The formula installs a signed binary from the release it names, and Homebrew verifies the
checksum before installing. `Formula/rankme.rb` is generated on every release from the same
`SHA256SUMS` the release itself verified — edits to it are overwritten.

## Licence

Copyright (c) 2026 Jatin Jain. All rights reserved. The formula is provided so that
`brew install` works; the collector it installs is proprietary and its source is not public.
