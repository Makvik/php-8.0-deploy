# Docker PHP for deploy

**Usage in Dockerfile:**
```Dockerfile
FROM makvik/php-8.0-deploy:latest
CMD ["php-fpm"]
```

**Usage in GitLabCI:**
```yml
image: makvik/php-8.0-deploy:latest
```

**Full Example usage in a GitLabCI:**
 - Example .gitlab-ci.yml.example

**Composition**
1. Php 8.0
	- Soap
	- Exif
	- GD
	- Imagick
2. Composer - 1.10.10
3. Node.js|Npm - 12.18.3|6.14.6
4. Python - 2.7
5. Rsync - 3.1.3
