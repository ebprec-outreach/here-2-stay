# Here2Stay

## Usage
Install the necessary dependencies with
```bash
npm install
```
then start the development server with
```bash
npm run dev
```
You should see the port that this is hosted on in the terminal output.

### A note on .env
When cloning and attempting to run a development environment, you will need to specify a `DATABASE_URL` in the `.env` file. This is a required step to preserve safety. This will be abstracted away to the Vercel deploy workflow so that `.env` don't need to be checked in to the repo.
