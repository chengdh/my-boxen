# This file manages Puppet module dependencies.
#
# It works a lot like Bundler. We provide some core modules by
# default. This ensures at least the ability to construct a basic
# environment.

def github(name, version, options = nil)
  options ||= {}
  options[:repo] ||= "boxen/puppet-#{name}"
  mod name, version, :github_tarball => options[:repo]
end

# Core modules for a basic development environment. You can replace
# some/most of those if you want, but it's not recommended.

# Includes many of our custom types and providers, as well as global
# config. Required.

github "boxen", "3.3.3"

# Core modules for a basic development environment. You can replace
# some/most of these if you want, but it's not recommended.

github "dnsmasq",  "1.0.0"
github "gcc",      "1.0.0"
github "git",      "1.0.0"
github "homebrew", "1.0.0"
github "hub",      "1.0.0"
github "inifile",  "0.9.0", :repo => "cprice-puppet/puppetlabs-inifile"
github "nginx",    "1.0.0"
github "nodejs",   "1.0.0"
github "nvm",      "1.0.0"
github "ruby",     "1.0.0"
github "stdlib",   "3.0.0", :repo => "puppetlabs/puppetlabs-stdlib"
github "sudo",     "1.0.0"

# Optional/custom modules. There are tons available at
# https://github.com/boxen.
github "sysctl",     	"1.0.0"
github "macvim",     	"1.0.0"
github "gitx",     	"1.0.0"
github "mysql",     	"1.0.0"
github "mysql_workbench",'1.0.0',:repo => "cdburgess/puppet-mysql_workbench"
github "postgresql",     "1.0.0"
github "screen",     "1.0.0"

github "xquartz",    "1.0.0"
github "python",     "1.1.1"
github "osx",     "1.0.0"
github "zsh",     "1.0.0"

#other tools
github "iterm2",     "1.0.0"
github "chrome",     "1.0.0"
github "imagemagick",     "1.2.0"
github "cyberduck",     "1.0.0"
github "alfred",     "1.0.0"
github "pkgconfig",     "1.0.0"
#github "dropbox",     "1.0.0"
github "tmux",     "1.0.0"
github "autojump",     "1.0.0"
github "wget",     "1.0.0"
github "things",     "1.0.0"
github "github",     "1.0.0",:repo => "pulse00/puppet-github"
github "yadr",     "0.0.4",:repo => "chengdh/boxen-yadr"
github "spotify",     "1.0.0"
github "sparrow",     "1.0.0"
github "flux",     "0.0.1"
github "daisy_disk",     "1.0.0"
