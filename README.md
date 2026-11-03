# github-final-project

A simple interest calculator project developed as part of the IBM "Introduction to Git and GitHub" course on Coursera / IBM Developer Skills Network.

## Purpose

The purpose of this repository is to provide a simple, clean, and interactive Bash script (`simple-interest.sh`) that calculates the simple interest accrued on a principal investment or loan over a specified time period at a given annual interest rate.

## Formula

The simple interest is calculated using the standard mathematical formula:

```text
Simple Interest = P * R * T / 100
```

Where:
- **P** = Principal amount (the initial amount of money borrowed or invested)
- **R** = Annual rate of interest (percentage per year)
- **T** = Time period in years (duration for which the money is borrowed or invested)

## Usage Guide & Script Instructions

### Prerequisites
- A Unix/Linux environment or a Bash shell (such as Git Bash on Windows, macOS Terminal, or Linux terminal).

### Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rushiketh07/github-final-project.git
   cd github-final-project
   ```

2. **Make the script executable:**
   ```bash
   chmod +x simple-interest.sh
   ```

3. **Run the script:**
   ```bash
   ./simple-interest.sh
   ```
   *Alternatively, run with Bash directly:*
   ```bash
   bash simple-interest.sh
   ```

4. **Input Prompts:**
   When prompted, enter the requested numeric values:
   - `Enter the principal:` (e.g., `1000`)
   - `Enter rate of interest per year:` (e.g., `5`)
   - `Enter time period in years:` (e.g., `2`)

5. **Expected Output:**
   ```text
   The simple interest is: 
   100
   ```

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for full details.

## Code of Conduct

Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) when contributing to this project.

## Contributing

We welcome community contributions! Please review our [Contributing Guidelines](CONTRIBUTING.md) to get started.
