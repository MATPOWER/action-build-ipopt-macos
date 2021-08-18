Build IPOPT (macOS)
===================

### GitHub Action to build [IPOPT][1] from source on macOS

Builds and installs COIN-OR's [IPOPT][1] from source on macOS runners using
`coinbrew` with the build prefix of `$HOME/install`.

### Inputs / Outputs

None.

### Example Usage
```
    steps:
    - name: Build Octave from source
      uses: MATPOWER/action-build-ipopt-macos@v1

    - name: Display installed files
      run: |
        ls -al $HOME/install/
        ls -al $HOME/install/bin
        ls -al $HOME/install/include
        ls -al $HOME/install/lib
        ls -al $HOME/install/share
```

[1]: https://github.com/coin-or/Ipopt
