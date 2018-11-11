## Fork diff

- add freetype cmake define WITH_HarfBuzz=OFF, because it causes compilation error
- to test package run `make test`
- update to 2.9.1
- deleted all files for ci
- deleted license file

## Installation hint

`conan remote add ckristen https://api.bintray.com/conan/ckristen/conan`
`freetype/2.9.1@ckristen/testing`

## Upload hint

`conan upload freetype/2.1.9@ckristen/testing -r ckristen --all`