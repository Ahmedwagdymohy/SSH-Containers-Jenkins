############################ Jenkins Dockerfile--working ############################
FROM jenkins/jenkins:lts

# Set environment variables
ENV JENKINS_HOME /var/jenkins_home

# Switch to the root user to install additional packages
USER root

# Update the package list and install additional tools
RUN apt-get update && apt-get install -y \
    nano \
    openssh-client \
    vim \
    curl \
    && rm -rf /var/lib/apt/lists/*



# Expose Jenkins web and agent ports
EXPOSE 8080 50000




