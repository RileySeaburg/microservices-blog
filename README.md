# microservices-blog

[microservices-blog-client](https://github.com/RileySeaburg/microservices-blog-client)

<!-- alert emoji -->
<details>
<summary>🚨Alert🚨</summary>
<h2>🚨 This project is not production ready 🚨</h2>
<p>🚨 It is still under construction 🚨</p>
</details>

This is a blog application built with microservices.

## Features

- [x] Create a post
- [x] Update a post
- [x] Delete a post
- [x] View a list of posts
- [x] View a single post
- [x] Create a comment
- [x] Update a comment
- [x] Delete a comment
- [x] View a list of comments
- [x] View a single comment

This application needs an event bus to communicate between services. It is had not been implemented yet.

## Development

### Prerequisites

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/en/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Kubernetes](https://kubernetes.io/)
- [Skaffold](https://skaffold.dev/)

### Getting Started

1. Clone the repository

```bash
git clone
```

2. Clone the client
    
```bash
git clone https://github.com/RileySeaburg/microservices-blog-client.git client
```

This project makes use of Skaffold to run the application in a Kubernetes cluster. Skaffold will build the Docker images for each service and deploy them to the cluster.

3. Start the Kubernetes cluster

```bash
skaffold dev
```

4. Update your hosts file

```bash
sudo nano 
- Windows: `C:\Windows\System32\drivers\etc\hosts`
- Mac: `/etc/hosts`
- Linux: `/etc/hosts`
```

Add the following line to the hosts file:

```bash
localhost posts.com
```

5. Navigate to the client

[http://posts.com](http://posts.com)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details



