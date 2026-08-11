# Fantasy-Football-Assistant
Windows desktop fantasy football draft and league analysis assistant.
# Fantasy Football Assistant

Fantasy Football Assistant is a Windows desktop application currently in active development. The goal of the project is to help fantasy football users make more informed decisions during the draft and throughout the season.

## Current Focus

The application is being built around Yahoo Fantasy Football first, with plans to support additional fantasy platforms in the future.

Current and planned features include:

* League-specific draft recommendations
* Live draft tracking
* Player rankings and available-player analysis
* Team-needs analysis
* Roster evaluation
* Mock draft simulation
* Draft history and correction tools
* Waiver and free-agent recommendations
* Player status and injury monitoring
* League-specific scoring analysis
* Season-long roster and matchup recommendations

## Yahoo Fantasy Sports Integration

Fantasy Football Assistant is designed to connect to a user's own Yahoo Fantasy account through OAuth authentication.

The application intends to use read-only Yahoo Fantasy Sports API access to retrieve information such as:

* League information
* League settings
* Teams
* Rosters
* Players
* Draft results
* Other fantasy football data needed for analysis

Users will only be able to access Yahoo Fantasy leagues that their authenticated Yahoo account is authorized to view.

The application does not currently require Yahoo Fantasy read/write access. It will not perform roster transactions, waiver claims, trades, or other account changes through the Yahoo API.

## Privacy and Security

Yahoo OAuth tokens are stored locally using Windows user-level encryption.

The application does not intentionally expose OAuth credentials, access tokens, refresh tokens, or other private Yahoo account information.

## Development Status

Fantasy Football Assistant is currently a private-development Windows desktop application and has not yet been publicly released.

The initial development focus is draft preparation and live draft assistance, followed by season-long roster, waiver, free-agent, and matchup analysis.

## Platform

* Windows desktop
* Python
* Yahoo Fantasy Football integration
* Local application database
* Secure OAuth authentication

## Project Status

This project is under active development. Features, architecture, and supported fantasy platforms may change as development continues.
