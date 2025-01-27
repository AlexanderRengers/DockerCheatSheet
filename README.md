# DockerCheatSheet
Commonly used docker commands

# Transform markdown.md to PDF
docker run --rm \
       --volume "$(pwd):/data" \
       --user $(id -u):$(id -g) \
       pandoc/latex README.md -o outfile.pdf