## First run on new device
1. Make sure the file "package-lock.json" and folder "node_modules" are not on the project

2. Install dependencies

   ```bash
   npm install --legacy-peer-deps
   ```

3. Start the app with caché clear

   ```bash
   npx expo start -c
   ```

## Next run's on device

Only need to run

   ```bash
   npx expo start
   ```
