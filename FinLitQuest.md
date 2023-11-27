# Project Name: FinLit Quest - A Financial Literacy Adventure Game

## 1. Introduction

### 1.1 Purpose
FinLit Quest is an educational game aimed at improving financial literacy among its players. It uses engaging gameplay to teach important financial concepts and encourage sound financial reasoning.

### 1.2 Intended Audience
The game is intended for individuals of all ages who wish to improve their financial literacy. While it is suitable for a general audience, it specifically targets young adults and teenagers who are beginning to navigate financial responsibilities.

### 1.3 Intended Use
FinLit Quest is designed to be both educational and entertaining. Players will learn about budgeting, saving, investing, and other financial concepts while enjoying an immersive game experience.

### 1.4 Scope
The scope of the project is to develop a game that is engaging yet informative within a two-month timeframe. The MVP will focus on core financial concepts and adapt to different literacy levels. Advanced features like multiplayer mode or complex investment simulations will not be included in the initial release.

#### Benefits
The game will provide an interactive and accessible way for players to learn about financial management, potentially leading to better personal financial decisions and an overall improvement in financial literacy.

#### Objectives
- To release an MVP within two months.
- To cover key financial concepts such as budgeting, saving, and basic investing.
- To implement an adaptive difficulty system based on player performance.

#### Goals
- Increase financial literacy among players.
- Receive positive feedback on user engagement and educational value.
- Lay the groundwork for future expansions and features.

### 1.5 Game-play Concept

This game is intended to be graphically simple, even low-tech or retro. Sprite-based, top-down gameplay is fine.

The charactor lives in a world that is quickly evolving through economic history. The stages of play are based on historic financial inventions that disrupted existing economic systems. Through the game, the player must master five stages of financial literacy to succeed through seven phases of economic history.

#### Game Play Phases
##### Phase 1: Barter System to Invention of Money
- **Characteristics:** Initially, economies operated on a barter system where goods were directly exchanged for other goods.
- **Disruptive Invention:** The creation of money (in various forms, like shells, metal coins) revolutionized trade by introducing a common medium of exchange.
- **Financial Literacy Stage 1:** Learning the basics of trade and value, akin to budgeting and saving, as players manage resources to meet their needs.

##### Phase 2: Coinage to Banking Systems
- **Characteristics:** Coins made from precious metals gained prominence, leading to standardized forms of money.
- **Disruptive Invention:** The establishment of banks and the concept of banking.
- **Financial Literacy Stage 1 & 2:** Introduction to currency, basic banking, saving techniques, and the concept of borrowing and lending.

##### Phase 3: Introduction of Paper Money
- **Characteristics:** Transition from coins to paper money.
- **Disruptive Invention:** The introduction of paper money.
- **Financial Literacy Stage 2 & 3:** Understanding paper currency, early investing, credit basics, and managing larger sums of money.

##### Phase 4: Digital Revolution and Electronic Trading
- **Characteristics:** Expansion of digital technology in finance.
- **Disruptive Invention:** Advent of computers and the internet transforming financial markets.
- **Financial Literacy Stage 4 & 5:** Electronic banking, online investing, understanding of digital economies, advanced portfolio management, and continuous education in financial trends.

#### Detailed Explanation of Stages of Financial Literacy
##### Stage 1: Financial Literacy Basics
1. **Budgeting and Expense Tracking:** Understanding how to create and stick to a budget, tracking daily, monthly, and yearly expenses.
2. **Basic Saving Techniques:** Learning the importance of saving, different methods to save, and setting up an emergency fund.
3. **Understanding Debt:** Basics of good debt vs. bad debt, understanding interest rates, and the impact of debt on financial health.
4. **Basic Banking Products:** Familiarity with checking and savings accounts, certificates of deposit (CDs), and basic banking services.

##### Stage 2: Intermediate Financial Knowledge
1. **Introduction to Investing:** Understanding stocks, bonds, mutual funds, and the importance of diversification.
2. **Retirement Planning Basics:** Introduction to retirement accounts like 401(k)s, IRAs, and the concept of compound interest.
3. **Credit Scores and Reports:** How credit scores are calculated, the importance of good credit, and how to read credit reports.
4. **Insurance Basics:** Understanding different types of insurance (health, life, auto) and their importance in financial planning.

##### Stage 3: Advanced Personal Finance
1. **Advanced Investing Concepts:** Learning about ETFs, options, index funds, and more sophisticated investment strategies.
2. **Tax Planning and Strategies:** Understanding how different investments are taxed, and basic tax planning strategies.
3. **Real Estate and Mortgages:** Basics of buying a home, understanding mortgages, and real estate as an investment.
4. **Estate Planning:** Wills, trusts, and planning for the transfer of assets.

##### Stage 4: Specialized Financial Knowledge
1. **Alternative Investments:** Introduction to commodities, real estate investment trusts (REITs), hedge funds, and private equity.
2. **Advanced Tax Strategies:** Delving into more complex tax reduction strategies, understanding tax implications of various investment vehicles.
3. **Risk Management and Advanced Insurance:** Learning about umbrella policies, long-term care insurance, and advanced risk management strategies.
4. **International Finance and Markets:** Understanding global markets, foreign exchange, and international investment strategies.

##### Stage 5: Mastery and Continuous Learning
1. **Economic Theory and Market Analysis:** Understanding macroeconomic and microeconomic theories, market trends, and economic indicators.
2. **Advanced Portfolio Management:** Tailoring investment portfolios to specific goals, risk tolerance, and market conditions.
3. **Behavioral Finance:** Understanding how psychology affects financial decisions and market outcomes.
4. **Continued Education and Adaptation:** Keeping up with the latest financial tools, technologies, and trends. Attending workshops, seminars, and possibly formal education in finance.

## 2. Product Roadmap

### Milestone 1: Initial Setup and Basic Application (End of Sprint 1)
- Establish development environments.
- Set up a minimal DevOps pipeline for automated testing and deployment.
- Develop the foundational game mechanics focusing on Phase 1: Barter System to Invention of Money.
- Introduce initial educational content for Stage 1: Financial Literacy Basics.

### Milestone 2: Core Feature Development and Phase 2 Implementation (One Month)
- Expand game mechanics to include Phase 2: Coinage to Banking Systems.
- Integrate educational modules for Stage 2: Intermediate Financial Knowledge.
- Develop and test adaptive difficulty system tailored to player progression.
- Rudimentary UI/UX for these phases.

### Milestone 3: Minimum Viable Product - Phase 3 Implementation (Two Months)
- Implement Phase 3: Introduction of Paper Money, focusing on more complex financial concepts.
- Introduce educational content for Stage 3: Advanced Personal Finance.
- Enhance UI/UX to production-quality for a better user experience.
- Ensure the game's adaptive difficulty system effectively scales with these advanced concepts.
- Prepare the game for public release as an MVP with the first three phases.

### Milestone 4: Feature Enhancement and Phase 4 Development (Three Months)
- Begin development of Phase 4: Digital Revolution and Electronic Trading.
- Integrate Stage 4: Specialized Financial Knowledge and Stage 5: Mastery and Continuous Learning modules.
- Implement additional game features and enhancements based on user feedback from the MVP.
- Improve and refine the game's graphics, sound, and overall player experience.
- Aim for complete functionality of all game phases and educational stages, with a focus on advanced financial literacy.

## 3. System Features and Requirements

### 3.1 Software Engineering Requirements
- Separate local, staging, and production environments.
- Modular architecture.
- Well-documented code and APIs.
- Automated testing with >90% test coverage.
- Peer review through PR reviews or pair programming.
- Automated deployment to staging and production environments.
- Monitoring and observability features for real-time performance tracking.

### 3.2 Functional Requirements Descriptions
- **Adaptive Difficulty System**: Adjusts game difficulty based on the player’s responses and progress to maintain engagement and learning effectiveness.
- **Educational Modules**: Interactive lessons covering essential financial topics.
- **Game Mechanics**: Core gameplay elements that simulate financial decision-making.

### 3.3 Nonfunctional Requirements Descriptions
- **Performance**: Smooth and responsive gameplay experience across platforms.
- **Scalability**: Cloud-native architecture for elastic scaling.
- **Availability & Reliability**: Regular backups and minimal downtime.
- **Security**: Data encryption and privacy protection.
- **Usability**: Intuitive, responsive UI design with accessibility support.
- **Data Governance**: Compliance with data protection regulations like GDPR and CCPA.
