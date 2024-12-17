# Maintainers Guide

See -> [/docs/docs/contributors/developers-guide/maintainers.md](/docs/docs/contributors/developers-guide/maintainers.md)



# Useful links
- [https://forum.cursor.com/t/dev-containers-support/1510] Using Cursor with dev containers
- [https://github.com/mealie-recipes/mealie/discussions/3436] Deploying to Fly.io

# Changes to get running
- Docker seemed to put the API on 9001 (instead of 9000), possibly due to conflict. In any case, I modified env.API_PORT in Taskfile.yml
