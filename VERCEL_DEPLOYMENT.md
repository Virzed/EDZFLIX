# VERCEL_DEPLOYMENT.md

## Deployment Instructions for NeroFlix

### Prerequisites
1. **Vercel Account**: Make sure you have an account on [Vercel](https://vercel.com/).
2. **Node.js**: Ensure Node.js is installed on your machine.
3. **Git**: Have Git installed for version control.

### Steps to Deploy

1. **Clone the Repository**
   ```bash
   git clone https://github.com/nero31994/neroflix.git
   cd neroflix
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Build the Project**
   ```bash
   npm run build
   ```

4. **Login to Vercel**
   ```bash
   npm i -g vercel
   vercel login
   ```

5. **Deploy to Vercel**
   ```bash
   vercel
   ```
   Follow the instructions to set your deployment preferences.

### Environment Variables
Make sure to set the following environment variables in your Vercel project settings:
- `DATABASE_URL`
- `API_KEY`

### Admin Credentials
Below are the admin credentials to access the admin dashboard:
- **Username**: admin@neroflix.com
- **Password**: securePassword123

### Additional Notes
- Ensure that the main branch is selected during the deployment process.
- If you encounter any issues, refer to the [Vercel Documentation](https://vercel.com/docs).

---

*This document was generated on 2026-02-05 02:06:56 UTC*