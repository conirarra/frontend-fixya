## First run on new device
1. Make sure the file "package-lock.json" and folder "node_modules" are not on the project

2. Install dependencies

   ```bash
   npm install --legacy-peer-deps
   ```

Note: A lot of warnings will appear, this is normal

3. Start the app with cache clear

   ```bash
   npx expo start -c
   ```

## Next run's on device

Only need to run

   ```bash
   npx expo start
   ```
