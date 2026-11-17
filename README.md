# Simple Interest Calculator

A lightweight command-line simple-interest calculator written in Bash.

## Overview

The script asks for a principal amount, an annual interest rate, and a time period in years. It then calculates the simple interest and prints the result to two decimal places.

## Formula

```text
Simple Interest = (Principal × Rate × Time) / 100
```

This project calculates **interest only**; it does not add the interest to the principal to calculate a maturity amount.

## Requirements

- Bash
- `bc` for decimal arithmetic

On Debian/Ubuntu, install `bc` with:

```bash
sudo apt-get update
sudo apt-get install bc
```

## Run the calculator

Clone the repository and move into the project directory:

```bash
git clone https://github.com/devoshreesaha2006/github-final-project.git
cd github-final-project
bash simple-interest.sh
```

You can also make the script executable and run it directly:

```bash
chmod +x simple-interest.sh
./simple-interest.sh
```

## Example

For a principal of 1000, an annual rate of 5%, and a time period of 3 years:

```text
Enter Principal Amount: 1000
Enter Rate of Interest (% per year): 5
Enter Time Period (in years): 3
Simple Interest = 150.00
```

## Project files

| File | Purpose |
| --- | --- |
| `simple-interest.sh` | Bash script that calculates simple interest |
| `README.md` | Project overview and usage instructions |
| `LICENSE` | Apache License 2.0 |
| `CODE_OF_CONDUCT.md` | Community participation guidelines |
| `CONTRIBUTING.md` | Contribution instructions |

## License

This project is licensed under the [Apache License 2.0](LICENSE).

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.
