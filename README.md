# winactivate

Easy-to-use Windows HWID/KMS38 Activation Script.

## Usage

Run the script as an administrator. That's it. Your copy of Windows should be activated.

If you explicitly want to use KMS38 activation, you can use the `/forcekms38` flag.

## Compatibility

This script is compatible with build 10240 and above.

## Troubleshooting

### Script doesn't detect Administrator privileges

Sometimes, it can happen that even though you have Administrator privileges, the script doesn't detect it. In this case, open a command prompt as administrator, navigate to the folder containing the script, and run the following command:

    winactivate.cmd /skipadmincheck

This skips the detection of Administrator privileges.

## Credits

- [mspaintmsi](https://github.com/mspaintmsi) for the rewritten version of `slc.dll`

## License

This project is licensed under the MIT license. Learn more about the license [here](LICENSE).
