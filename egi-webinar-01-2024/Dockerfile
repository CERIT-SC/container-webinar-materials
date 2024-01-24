FROM nginxinc/nginx-unprivileged

# Copy the static site
COPY --chown=nginx:nginx ./application /usr/share/nginx/html

# Expose ports
EXPOSE 8080

# Run nginx
CMD ["nginx", "-g", "daemon off;"]