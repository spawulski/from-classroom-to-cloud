# From Classroom to Cloud: A Student's Journey in Tech

Welcome to the resources and references from my tech conference talk! This repository contains curated materials to help students navigate their journey from academic learning to professional cloud engineering.

## 📚 Recommended Books

### The Phoenix Project
A novel about IT, DevOps, and helping your business win. This book tells the story of an IT manager who must learn to think and work differently to save his company from disaster. It's an excellent introduction to DevOps principles and how technology teams can work more effectively.

### Staff Engineer: Leadership Beyond the Management Track
A comprehensive guide for engineers who want to grow their impact without becoming managers. This book explores different paths for senior engineers and provides practical advice on technical leadership, architecture decisions, and career development.

## 🌐 Essential Resources

### [levels.fyi](https://levels.fyi)
A comprehensive platform for understanding tech industry compensation, career levels, and company insights. Essential for students to understand market rates and career progression in tech companies.

## 📖 Must-Read Articles

### [How to be a -10x Engineer](https://taylor.town/-10x)
A satirical but insightful article that highlights common anti-patterns in engineering teams. While humorous, it provides valuable lessons about what NOT to do as an engineer, helping students understand the importance of good engineering practices, clear communication, and effective teamwork.

## 🎯 Key Takeaways

- **Continuous Learning**: The tech industry evolves rapidly - stay curious and keep learning
- **Soft Skills Matter**: Technical skills are important, but communication and collaboration are equally crucial
- **Career Paths**: There are multiple ways to grow in tech beyond traditional management tracks
- **Industry Awareness**: Understanding compensation, company culture, and market trends helps make informed career decisions
- **Best Practices**: Learn from both positive examples and common pitfalls to develop good engineering habits

## 🏠 Homelabbing: Hands-On Learning

Transform your old laptop or Raspberry Pi into a powerful learning environment! Homelabbing is one of the best ways to gain practical experience with cloud technologies, DevOps tools, and system administration.

### Getting Started Resources

- **[r/homelab](https://reddit.com/r/homelab)** - Reddit community with guides, project ideas, and troubleshooting help
- **[Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)** - Curated list of self-hosted applications
- **[Home Lab Beginners Guide](https://www.reddit.com/r/homelab/wiki/beginnersguide)** - Comprehensive starter guide
- **[Raspberry Pi Projects](https://projects.raspberrypi.org/)** - Official Raspberry Pi project tutorials
- **[Proxmox VE](https://www.proxmox.com/en/proxmox-ve)** - Free virtualization platform for homelabs
- **[TrueNAS Scale](https://www.truenas.com/truenas-scale/)** - Open-source NAS OS with container and VM support
- **[Docker](https://docs.docker.com/get-started/)** - Containerization platform perfect for homelab projects
- **[Kubernetes on Raspberry Pi](https://kubernetes.io/docs/setup/production-environment/turnkey/on-premises/)** - Run Kubernetes clusters at home

### Popular Homelab Projects

- **Media Server**: Plex, Jellyfin, or Emby for streaming
- **Home Automation**: Home Assistant for smart home control
- **Monitoring**: Grafana + Prometheus for system monitoring
- **Backup Solutions**: Nextcloud for personal cloud storage
- **Development Environment**: GitLab, Jenkins, or GitHub Actions runners
- **Network Services**: Pi-hole for ad blocking, VPN servers
- **Personal Website**: Deploy a simple website on your homelab and expose it to the internet using Cloudflare Tunnels

### 🌐 Exposing Your Homelab to the Internet

One of the most exciting homelab projects is deploying your own website and making it accessible worldwide! Here's how to get started:

**Cloudflare Tunnels** provide a secure way to expose your homelab services to the internet without opening ports on your router or dealing with dynamic IP addresses. This is perfect for:

- **Personal portfolios** and project showcases
- **Learning web development** with real-world deployment
- **Understanding reverse proxies** and modern networking
- **Practicing DevOps** with CI/CD pipelines to your homelab

**Getting Started:**
1. Deploy a simple web server (nginx, Apache, or containerized app) on your homelab
2. Install Cloudflare Tunnel (`cloudflared`) on your homelab machine
3. Configure the tunnel to route traffic from your domain to your local service
4. Update your DNS records in Cloudflare to point to your tunnel

This approach teaches you about DNS, reverse proxies, SSL certificates, and modern web deployment practices - all essential skills for cloud engineering!

### 💻 Hardware Recommendations

- **Raspberry Pi 4** (4GB+ RAM) - Great for learning Linux and containerization
- **Old Laptop/Desktop** - Perfect for running virtual machines and heavier workloads
- **Mini PC** (Intel NUC, Beelink) - Compact but powerful for homelab servers

## 🌟 Getting Involved with CNCF Open Source

The Cloud Native Computing Foundation (CNCF) is home to some of the most important cloud technologies like Kubernetes, Prometheus, and Helm. Getting involved is an excellent way to learn from industry experts and contribute to projects that power the modern internet.

### How to Get Started

**1. Attend CNCF Community Meetings**
- **[CNCF Calendar](https://www.cncf.io/community/calendar/)** - Find weekly meetings for various projects
- **[Kubernetes Community Meetings](https://github.com/kubernetes/community/tree/master/communication)** - Weekly SIG meetings and community calls
- **[CNCF Slack](https://slack.cncf.io/)** - Join the community workspace for real-time discussions
- **[CNCF YouTube Channel](https://www.youtube.com/c/CloudNativeComputingFoundation)** - Watch recorded meetings and talks

**2. Find Your First Contribution**
- **[CNCF Landscape](https://landscape.cncf.io/)** - Explore all CNCF projects and find ones that interest you
- **[Good First Issues](https://github.com/cncf/foundation/blob/main/mentoring/lfx-mentorship/2023/README.md)** - Look for beginner-friendly issues
- **[CNCF Mentorship Programs](https://github.com/cncf/mentoring)** - Apply for structured learning programs
- **[Kubernetes Contributing Guide](https://github.com/kubernetes/community/blob/master/contributors/guide/README.md)** - Comprehensive guide for Kubernetes contributions

**3. Join Special Interest Groups (SIGs)**
- **[Kubernetes SIGs](https://github.com/kubernetes/community/tree/master/sig-list)** - Find SIGs that match your interests
- **[CNCF Working Groups](https://github.com/cncf/toc/tree/main/workinggroups)** - Join working groups on specific topics
- **[CNCF Ambassadors](https://www.cncf.io/people/ambassadors/)** - Learn about becoming a community ambassador

**4. Attend Events**
- **[KubeCon + CloudNativeCon](https://events.linuxfoundation.org/about/kubecon-cloudnativecon/)** - Major annual conference
- **[CNCF Meetups](https://www.meetup.com/pro/cncf/)** - Local community meetups worldwide
- **[CNCF Webinars](https://www.cncf.io/webinars/)** - Regular educational webinars

### Tips for Students

- **Start Small**: Begin with documentation improvements or bug fixes
- **Be Consistent**: Regular participation builds relationships and expertise
- **Ask Questions**: The community is welcoming to newcomers
- **Follow Code of Conduct**: CNCF has strict guidelines for respectful participation
- **Document Your Journey**: Share your learning process on social media or blogs

## 🚀 Next Steps

1. Read the recommended books to understand industry practices
2. Explore levels.fyi to research companies and compensation
3. Reflect on the anti-patterns mentioned in the -10x engineer article
4. Start a homelab project with Raspberry Pi or old hardware
5. Build projects and contribute to open source
6. Network with professionals in your area of interest

## 📧 Contact

**Email:** [spawulski@lotlinx.com](mailto:spawulski@lotlinx.com)
**LinkedIn:** [linkedin.com/in/s-m-p/](https://www.linkedin.com/in/s-m-p/)

---

*This repository serves as a companion to my conference talk. Feel free to star, fork, or contribute additional resources that would be valuable for students entering the tech industry.*
