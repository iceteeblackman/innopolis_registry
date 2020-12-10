# innopolis_registry

For action:


docker run -d -p 5000:5000 --restart always --name registry -e REGISTRY_AUTH:itbm -e REGISTRY_AUTH_HTPASSWD_REALM:12345678 -e REGISTRY_AUTH_HTPASSWD_PATH:/auth/registry.password -e REGISTRY_STORAGE_FILESYSTEM_ROOTDIRECTORY:/data -v /data:/data -v /data/auth:/auth registry:2
