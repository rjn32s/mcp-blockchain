# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.2] - 2025-04-13

### Fixed
- Fixed package installation issues with uvx
- Added proper version handling in package
- Improved package structure for better compatibility
- Fixed import path resolution

## [0.1.1] - 2025-04-13

### Fixed
- Fixed package structure for proper installation
- Corrected entry point configuration in pyproject.toml
- Removed setup.py in favor of pyproject.toml
- Added src root __init__.py for correct package resolution

## [0.1.0] - 2024-04-13

### Added
- Initial release of MCP Blockchain server
- Ethereum Address Validator with checksum verification
- Gas Fee Estimator using public RPC endpoints
- Wallet Balance Checker with fallback RPCs
- Smart Contract Ownership Checker with proxy contract support
- Transaction Cost Calculator for various transaction types

### Features
- Support for basic ETH transfers
- ERC20 token transfer cost estimation
- NFT transfer cost estimation
- Uniswap swap cost estimation
- Contract deployment cost estimation
- Automatic RPC endpoint fallback
- Proxy contract detection and analysis

### Technical
- Async/await support for all operations
- Error handling with informative messages
- Test coverage for edge cases
- Modular code structure
- Public RPC endpoints (no API keys required)
- Exponential backoff for failed RPC calls
- Type hints and documentation

### Fixed
- Improved error handling for invalid inputs
- Enhanced proxy contract detection reliability
- Better gas fee estimation accuracy
- Robust RPC connection handling 