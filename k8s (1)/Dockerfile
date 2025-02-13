FROM node:21

# Set the working directory in the container
WORKDIR /app

# Copy the application code
COPY index.js .

# Run npm init to generate package.json (if necessary)
RUN npm init -y

# Expose the port the app will run on
EXPOSE 8080

# Start the Node.js app
CMD ["node", "index.js"]
