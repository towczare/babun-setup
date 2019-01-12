# Babun Setup

## Installing Babun

## Installing custom packages

1. Run following command to find given module:
```
pact find zip
```
2. To install given module, run:
```
pact install zip
```

## Installing SDK Man
1. Run following method:
```
curl -s "https://get.sdkman.io" | bash
```
2. Restart your babun terminal
3. Run `sdk help` to confirm
```
{ ~ }  » sdk help                                                                               ~
==== BROADCAST =================================================================
* 12/01/19: Springboot 2.1.2.RELEASE released on SDKMAN! #springboot
* 11/01/19: Springboot 2.0.8.RELEASE released on SDKMAN! #springboot
* 11/01/19: Springboot 1.5.19.RELEASE released on SDKMAN! #springboot
================================================================================

Usage: sdk <command> [candidate] [version]
       sdk offline <enable|disable>

   commands:
       install   or i    <candidate> [version]
       uninstall or rm   <candidate> <version>
       list      or ls   [candidate]
       use       or u    <candidate> [version]
       default   or d    <candidate> [version]
       current   or c    [candidate]
       upgrade   or ug   [candidate]
       version   or v
       broadcast or b
       help      or h
       offline           [enable|disable]
       selfupdate        [force]
       update
       flush             <broadcast|archives|temp>

   candidate  :  the SDK to install: groovy, scala, grails, gradle, kotlin, etc.
                 use list command for comprehensive list of candidates
                 eg: $ sdk list

   version    :  where optional, defaults to latest stable if not provided
                 eg: $ sdk install groovy

```
