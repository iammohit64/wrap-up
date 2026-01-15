# Wrap-Up: Decentralized Articles Curation Platform

<div align="center">

![Wrap-Up Logo](https://img.shields.io/badge/Wrap--Up-Decentralized%20Truth-10b981?style=for-the-badge)

**The Intelligence Layer for the Verifiable Web**

[![Mantle](https://img.shields.io/badge/Mantle-Sepolia-orange.svg)](https://explorer.sepolia.mantle.xyz)
[![React](https://img.shields.io/badge/React-19.1.1-61DAFB.svg?logo=react)](https://reactjs.org/)
[![Solidity](https://img.shields.io/badge/Solidity-0.8.30-363636.svg?logo=solidity)](https://soliditylang.org/)

[Live Demo](https://wrap-up-one.vercel.app) • [Documentation](#setup-guide)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Architecture](#-architecture)
- [Folder Structure](#-folder-structure)
- [Smart Contracts](#-smart-contracts)
- [Setup Guide](#-setup-guide)
- [Usage](#-usage)
- [API Reference](#-api-reference)
- [Future Enhancements](#-future-enhancements)

---

## 🌟 Overview

**Wrap-Up** is a decentralized document curation platform built on the Mantle blockchain that enables users to scrape, analyze, and curate articles with verifiable on-chain records. The platform combines AI-powered content analysis with blockchain technology to create a transparent, community-driven news ecosystem.

### The Problem

- Traditional news platforms lack transparency in curation
- Centralized content moderation leads to bias
- No verifiable record of article popularity or engagement
- Readers cannot trust content authenticity

### Our Solution

Wrap-Up creates a **decentralized curation layer** where:
- Articles are scraped and analyzed using AI
- Summaries are stored on IPFS for permanence
- Curation records are immutably stored on Mantle blockchain
- Community voting creates transparent article rankings
- Users earn $MFD tokens for quality contributions

---

## ✨ Key Features

### 🤖 AI-Powered Analysis
- **Intelligent Scraping**: Extracts content from any article URL using metascraper
- **Multi-Platform Support**: Works with standard articles, LinkedIn posts, and Twitter/X
- **Smart Summarization**: Uses Groq AI (Llama 3.1) to generate:
  - Quick summaries (50-80 words)
  - Detailed analysis (200-300 words)
  - Key takeaways and statistics
  - Condensed content for easy reading

### ⛓️ Blockchain Integration
- **On-Chain Curation**: Articles minted as permanent blockchain records
- **IPFS Storage**: Decentralized content storage via Pinata
- **Smart Contract Voting**: Transparent upvoting system
- **User Points System**: Earn points for contributions
- **Token Rewards**: Claim $MFD tokens based on accumulated points

### 💬 Community Engagement
- **Nested Comments**: Support for replies and discussions
- **Comment Voting**: Upvote valuable comments
- **Leaderboard**: Top articles ranked by engagement score
- **User Profiles**: Custom display names stored on-chain
- **Anonymous Participation**: Comment without wallet connection

### 🎨 Modern UI/UX
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Dark Theme**: Eye-friendly interface with emerald accents
- **Real-time Updates**: Live contract event listening
- **Optimistic UI**: Instant feedback with background syncing
- **Toast Notifications**: Clear user feedback for all actions

---

## 🛠️ Technology Stack

### Frontend
| Technology | Version | Purpose |
|------------|---------|---------|
| **React** | 19.1.1 | UI framework |
| **Vite** | 7.1.7 | Build tool & dev server |
| **Tailwind CSS** | 4.1.16 | Styling framework |
| **React Router** | 7.9.5 | Client-side routing |
| **Zustand** | 5.0.8 | State management |
| **Wagmi** | 2.19.1 | Ethereum interactions |
| **Viem** | 2.38.5 | Ethereum utilities |
| **Web3Modal** | 5.1.11 | Wallet connection |
| **React Hot Toast** | 2.6.0 | Notifications |
| **Axios** | 1.13.1 | HTTP client |
| **Lucide React** | 0.548.0 | Icon library |

### Backend
| Technology | Version | Purpose |
|------------|---------|---------|
| **Node.js** | - | Runtime environment |
| **Express** | 5.1.0 | Web framework |
| **Prisma** | 6.18.0 | Database ORM |
| **MongoDB** | - | Database |
| **Groq SDK** | 0.34.0 | AI summarization |
| **Metascraper** | 5.49.5 | Web scraping |
| **Cheerio** | 1.1.2 | HTML parsing |
| **Axios** | 1.13.1 | HTTP requests |
| **Pinata** | - | IPFS gateway |

### Smart Contracts
| Technology | Version | Purpose |
|------------|---------|---------|
| **Solidity** | 0.8.30 | Smart contract language |
| **Foundry** | - | Development framework |
| **OpenZeppelin** | 5.5.0 | Contract libraries |
| **Mantle Sepolia** | - | Test network |

### DevOps & Deployment
- **Vercel**: Frontend hosting
- **Render**: Backend hosting
- **MongoDB Atlas**: Database hosting
- **Pinata**: IPFS pinning service

---

## 🏗️ Architecture
