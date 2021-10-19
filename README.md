# Docker
Repo for practicing docker.

## Resources
**Smaller build size**\
https://medium.com/trendyol-tech/how-we-reduce-node-docker-image-size-in-3-steps-ff2762b51d5a

### Commands

**List image**\
`docker images`

**Build image**\
`docker build --tag <name> <path>`

**Build image**\
`docker run <tag>`

**Analyze image size**\
`docker history --human --format "{{.CreatedBy}}: {{.Size}}" <tag>`