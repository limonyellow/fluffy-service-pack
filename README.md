# Fluffy Service Pack

## Overview

This service pack will help you relax with some fulffy sounds.

## Installation

`brew install limonyellow/fulffy-service-pack/fluffy-service-pack`

## Usage

`fsp so`

## Requirements

- macOS
- afplay

## Update Routine
1. Create and upload new version:  
`git tag -a v<vesion_tag> -m "version <vesion_tag>"`  
`git push origin v<vesion_tag>`  

2. Copy the link of the release tar.gz and run the command:  
`brew create https://github.com/limonyellow/fluffy-service-pack/archive/refs/tags/v<version_tag>.tar.gz`  
A new .rb file will be created.  
  
3. Copy the `url` and `sha256` values into the homebrew repo at https://github.com/limonyellow/homebrew-fulffy-service-pack/blob/main/fluffy-service-pack.rb

4. Run:  
`brew upgrade fluffy-service-pack`
