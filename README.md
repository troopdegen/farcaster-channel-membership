# Channel Membership Frame for Farcaster

## Project Description

This Frame enables channel gating for Farcaster communities, allowing users to apply for membership based on both onchain and off-chain validation. It supports token-gating via NFTs or ERC-20 balances, reputation-gating using external APIs, and social network activity checks, automating access control for channels.

## Why use this Frame?

Managing access to Farcaster channels often requires manual validation, which is time-consuming and prone to errors. This Frame automates the validation process by integrating various onchain and off-chain checks, ensuring that only qualified users gain access to the channel.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/fruteroclub/farcaster-membership-frame.git
   cd farcaster-membership-frame
   ```

2. Install dependencies:

   ```bash
   bun install
   ```

3. Run the development server:

   ```bash
   bun run dev
   ```

4. Open your browser and navigate to `http://localhost:3000/api/dev` to view the Frame in action (locally).

## Deployment on Vercel

To deploy the Channel Membership Frame on Vercel:

1. Push your project to a Git repository (GitHub, GitLab, etc.).
2. In your Vercel dashboard, select **New Project** and import your repository.
3. During the setup, Vercel will automatically detect the use of **bun** and **frog** for deployment. Ensure that the correct build and development commands are set:
   - **Build Command:** `bun run build`
   - **Output Directory:** `out`
4. Add any necessary environment variables under the **Settings** tab.
5. Deploy your project by clicking **Deploy**. Vercel will handle the deployment process, and your Frame will be live.

For more detailed Vercel deployment instructions, refer to the [Vercel documentation](https://vercel.com/docs).
