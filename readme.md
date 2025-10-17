# 🚀 Natural Language as Code

## 👋 Bye Bye Terraform, Welcome Natural Language Infrastructure! 

Tired of writing complex YAML configurations and remembering countless Terraform syntax rules? Say hello to the future of infrastructure management - **Natural Language as Code**! 

Instead of this complicated Terraform:

```hcl
resource "kubernetes_deployment" "app" {
  metadata {
    name      = "my-app"
    namespace = "production"
    labels = {
      app = "my-app"
    }
  }
  spec {
    replicas = 3
    selector {
      match_labels = {
        app = "my-app"
      }
    }
    template {
      metadata {
        labels = {
          app = "my-app"
        }
      }
      spec {
        container {
          image = "nginx:1.21"
          name  = "nginx"
          port {
            container_port = 80
          }
        }
      }
    }
  }
}
```

Just say:
> **"Deploy nginx application with 3 replicas in production namespace"**

And watch the magic happen! ✨

## Demo Video

[Watch the Natural Language as Code Demo](./aws_nlp.mp4) - download view raw
[![Natural Language as Code Demo](./aws_nlp_full.gif)]

---

##  Overview

**Natural Language as Code** revolutionizes infrastructure management by allowing DevOps engineers to describe their infrastructure needs in plain English.
All you need is VS Code, AWS CCAPI MCP server, and Claude Sonnet 4 to get started.
### Why Natural Language as Code?

**🎯 Intuitive**
___
Write infrastructure code the way you think about it

**⚡ Fast**
___
Deploy complex applications in seconds, not hours

**📚 Learning-Friendly**
___
Perfect for teams transitioning to cloud-native

---

### 🔮 What's Next?

  🤖 Coming Soon: I'll teach my chatbot at 🌐 https://apps.infraid.gr/ to do it too… it's already asking for coffee breaks!

<img width="1711" height="898" alt="image" src="https://github.com/user-attachments/assets/7f20a98b-e896-4113-a035-bde374a5d10e" />

___
**🚀 Ready to revolutionize your infrastructure management?**
