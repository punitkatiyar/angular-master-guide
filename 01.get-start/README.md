# Angular Local Setup For Devemopment 

```
Microsoft Windows [Version 10.0.22621.4317]
(c) Microsoft Corporation. All rights reserved.

C:\angular>npm install -g @angular/cli

added 271 packages in 20s

52 packages are looking for funding
  run `npm fund` for details

C:\angular>ng new helloApp

Would you like to share pseudonymous usage data about this project with the Angular Team
at Google under Google's Privacy Policy at https://policies.google.com/privacy. For more
details and how to change this setting, see https://angular.dev/cli/analytics.

   Yes

Thank you for sharing pseudonymous usage data. Should you change your mind, the following
command will disable this feature entirely:

    ng analytics disable --global

Global setting: enabled
Local setting: No local workspace configuration file.
Effective status: enabled
√ Which stylesheet format would you like to use? CSS             [ https://developer.mozilla.org/docs/Web/CSS
          ]
√ Do you want to enable Server-Side Rendering (SSR) and Static Site Generation (SSG/Prerendering)? Yes
√ Would you like to use the Server Routing and App Engine APIs (Developer Preview) for this server application? Yes
CREATE helloApp/angular.json (2855 bytes)
CREATE helloApp/package.json (1271 bytes)
CREATE helloApp/README.md (1530 bytes)
CREATE helloApp/tsconfig.json (942 bytes)
CREATE helloApp/.editorconfig (331 bytes)
CREATE helloApp/.gitignore (629 bytes)
CREATE helloApp/tsconfig.app.json (508 bytes)
CREATE helloApp/tsconfig.spec.json (449 bytes)
CREATE helloApp/.vscode/extensions.json (134 bytes)
CREATE helloApp/.vscode/launch.json (490 bytes)
CREATE helloApp/.vscode/tasks.json (980 bytes)
CREATE helloApp/src/main.ts (256 bytes)
CREATE helloApp/src/index.html (307 bytes)
CREATE helloApp/src/styles.css (81 bytes)
CREATE helloApp/src/main.server.ts (271 bytes)
CREATE helloApp/src/server.ts (1674 bytes)
CREATE helloApp/src/app/app.component.html (20239 bytes)
CREATE helloApp/src/app/app.component.spec.ts (951 bytes)
CREATE helloApp/src/app/app.component.ts (296 bytes)
CREATE helloApp/src/app/app.component.css (0 bytes)
CREATE helloApp/src/app/app.config.ts (447 bytes)
CREATE helloApp/src/app/app.routes.ts (80 bytes)
CREATE helloApp/src/app/app.config.server.ts (519 bytes)
CREATE helloApp/src/app/app.routes.server.ts (174 bytes)
CREATE helloApp/public/favicon.ico (15086 bytes)
√ Packages installed successfully.
'git' is not recognized as an internal or external command,
operable program or batch file.

C:\angular>cd helloApp

C:\angular\helloApp>npm start

> hello-app@0.0.0 start
> ng serve


Would you like to share pseudonymous usage data about this project with the Angular Team
at Google under Google's Privacy Policy at https://policies.google.com/privacy. For more
details and how to change this setting, see https://angular.dev/cli/analytics.

   Yes

Thank you for sharing pseudonymous usage data. Should you change your mind, the following
command will disable this feature entirely:

    ng analytics disable

Global setting: enabled
Local setting: enabled
Effective status: enabled
Component HMR has been enabled.
If you encounter application reload issues, you can manually reload the page to bypass HMR and/or disable this feature
with the `--no-hmr` command line option.
Please consider reporting any issues you encounter here: https://github.com/angular/angular-cli/issues

Browser bundles
Initial chunk files  | Names            |  Raw size
polyfills.js         | polyfills        |  90.20 kB |
main.js              | main             |  23.23 kB |
styles.css           | styles           |  95 bytes |

                     | Initial total    | 113.52 kB


Server bundles
Initial chunk files  | Names            |  Raw size
polyfills.server.mjs | polyfills.server | 572.91 kB |
main.server.mjs      | main.server      |  24.56 kB |
server.mjs           | server           |   1.86 kB |

Application bundle generation complete. [3.114 seconds]

Watch mode enabled. Watching for file changes...
NOTE: Raw file sizes do not reflect development server per-request transformations.
  ➜  Local:   http://localhost:4200/
  ➜  press h + enter to show help

```
