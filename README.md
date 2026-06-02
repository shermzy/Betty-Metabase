# Rebase

Rebase is a self-hosted analytics workspace based on the Metabase Open Source Edition.

This fork keeps the upstream licensing boundaries intact:

- Open Source Edition code remains under the GNU Affero General Public License.
- Commercial/Enterprise code remains subject to the Metabase Commercial License.
- Rebase does not bypass license gates or enable commercial features without a valid license.

## Coolify Deployment

The included Coolify configuration runs the official Open Source Metabase image with Rebase product settings:

- Service name: `Rebase`
- Public URL: `https://rebase.app.t3ai.xyz`
- Application database: PostgreSQL
- Site name: `Rebase`

Use `docker-compose.coolify.yml` for the Coolify service configuration.

## Upstream

Rebase is forked from [Metabase](https://github.com/metabase/metabase). For upstream documentation, development guidance, and feature references, see the Metabase project and documentation.

## License

This repository contains source code originally from Metabase. The Open Source edition is released under the AGPL, while commercial editions and Enterprise features are released under the Metabase Commercial Software License.

See [LICENSE.txt](./LICENSE.txt) and the upstream license notices for details.
