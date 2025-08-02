# Shell Scripting Practice

This folder contains a collection of beginner to intermediate-level shell scripts written for practice and educational purposes. Each script demonstrates a specific functionality using shell scripting and standard Unix/Linux tools.

## Files and Descriptions

| Filename                  | Description                                                                                    |
| ------------------------- | ---------------------------------------------------------------------------------------------- |
| `1-create_global_var.sh`  | Creates a global variable `BEST` with the value `School`.                                      |
| `2-add_env_variable.sh`   | Adds 128 to the value stored in the environment variable `TRUEKNOWLEDGE`.                      |
| `3-divide_env_vars.sh`    | Divides the value of environment variable `POWER` by `DIVIDE`.                                 |
| `4-power_env_vars.sh`     | Raises `BREATH` to the power of `LOVE` using `bc`.                                             |
| `5-base2_to_base10.sh`    | Converts a binary number stored in `BINARY` to base 10.                                        |
| `6-combinations.sh`       | Prints all 2-letter combinations from `aa` to `zz`, excluding `oo`.                            |
| `7-two_decimal_places.sh` | Prints the number in `NUM` with two decimal places.                                            |
| `8-decimal_to_hex.sh`     | Converts a base-10 number in `DECIMAL` to base-16 (hex).                                       |
| `9-rot13.sh`              | Encodes and decodes text using the ROT13 algorithm.                                            |
| `10-odd_lines.sh`         | Prints every other (odd-numbered) line from input.                                             |
| `11-add_custom_base.sh`   | Adds two numbers in custom bases from env vars `WATER` and `STIR`, outputs in `bestchol` base. |

## Usage

1. Make sure you give execute permission to the script:

   ```bash
   chmod +x script_name.sh
   ```

2. Set the required environment variables before running a script. For example:

   ```bash
   export WATER=1010
   export STIR=11
   export water=2
   export stir=10
   export bestchol=16
   ./11-add_custom_base.sh
   ```

## Requirements

* Unix/Linux environment
* `bash` shell
* `bc` command-line calculator (for scripts using base conversion or arithmetic)
