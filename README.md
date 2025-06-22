# CyberSuite

CyberSuite is a collection of powerful cybersecurity tools designed for reconnaissance, analysis, and more. **CyberSift**, the first tool in this suite, is a reconnaissance tool for discovering domains, subdomains, and sensitive endpoints.

## CyberSift Features
- Discover related domains with different TLDs (e.g., example.com, example.org).
- Identify subdomains and sensitive endpoints (e.g., admin panels, .env files).
- Generate HTML reports with centered tables and filtering.
- Cyber-themed design with a sleek dark palette! 😎

## How to Use CyberSift
1. Visit [idovedu.github.io](https://idovedu.github.io).
2. Download the CyberSift tool (`cybersift.py`), sample outputs (e.g., assets.txt), and wordlists from the "Download Resources" section.
3. Read the usage guide on the page.
4. Run the tool:
   ```bash
   python cybersift.py -f domain.txt -o recon_results -c -np -t 20
   ```

## Recommended Tools
- **Subfinder**: Subdomain enumeration.
- **Nuclei**: Vulnerability scanning.
- **dnsx**: DNS record analysis.

## Issues
For questions, open an issue at [GitHub Issues](https://github.com/idovedu/CyberSuite/issues).

## License
Released under the MIT License.
