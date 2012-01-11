# iq_gem

Builds a specified .gemspec, pushes the .gem file to gems.innoq.com and recreates the index.
Consider it your *poor-man's-private-gem-server-release-tool™*.

## Setup

1. `git clone git://github.com/innoq/iq_gem.git`
2. Define `alias iq_gem=~/your_folder/iq_gem/iq_gem` in your `.bash_profile`, add the repository to your `PATH` or create a symlink in a directory in your `PATH`

## Usage

```
iq_gem --gemspec YOUR_GEM.gemspec --tag x.x.x --gem-repo REPO_DIR
```

For a list of possible command options use:

`iq_gem --help`
