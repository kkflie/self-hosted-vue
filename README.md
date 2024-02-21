1. Fill DSN in Sentry.init in src/main.js

2. Fill org and project in vite.config.js

3. yarn && yarn uploadSourcemap && yarn build

4. npx serve dist

5. click button which is "test error report"

6. open sentry issue pane to check if the stack tree has pinpointed the problem to the source code.