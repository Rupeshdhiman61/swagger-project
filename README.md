https://peterevans.dev/posts/how-to-host-swagger-docs-with-github-pages 

Make sure in the index.html, you mention the folder where the files are along with the file name correctly. 

for example dist/src.md

make sure to remove this line, else it will always go back to petstore api

<script src="dist/swagger-initializer.js" charset="UTF-8"> </script>