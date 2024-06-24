If this appears when running shell script:  "zsh: operation not permitted: ./test.sh"
Use the following to unlock the script:

xattr -d com.apple.quarantine ./test.sh
