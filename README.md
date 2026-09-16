# Los Paisanos BSA Tracking

Static application using Supabase authentication and company-isolated database records.

Publish the contents of this folder to the root of the `Los2025/Los-paisanos-app` repository. GitHub Pages should serve the `main` branch root. The expected address is https://los2025.github.io/Los-paisanos-app/.

Each new account creates a private company workspace. Company names are display labels: choosing another company's name does not grant access to its records. This version provides one account per workspace; staff invitations are not implemented.

The Supabase publishable key in `index.html` is intended for browser use. Access is enforced by database row-level policies. Never place a Supabase secret or service-role key in this repository.

`supabase.js` is the locally bundled Supabase JavaScript SDK, version 2.116.0, distributed under the MIT license in `SUPABASE-LICENSE.txt`.

Configure Supabase Authentication's Site URL and allowed redirects to the published address before relying on confirmation or password reset emails.
