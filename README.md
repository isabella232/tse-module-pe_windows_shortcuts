pe_windows_shortcuts
====================

Puppet Enterprise desktop shortcuts for Windows 2k8/2k12


usage
====================

In site.pp

if $::osfamily == 'windows' {
  class { "pe_windows_shortcuts":
    user => 'vagrant',
  }
}
