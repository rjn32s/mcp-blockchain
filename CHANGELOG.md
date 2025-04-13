# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2025-04-13

### Added
- Initial release
- Ethereum address validation tool
- Gas fee estimation with multiple RPC fallbacks
- Wallet balance checker
- Smart contract ownership checker with proxy support
- Transaction cost calculator for different operation types
- Comprehensive test suite with async support
- GitHub Actions CI/CD pipeline
- Multiple public RPC endpoint support with fallback mechanism
- EIP-1967 proxy contract detection and handling
- Retry mechanism with exponential backoff for RPC calls

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