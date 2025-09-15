# 🚀 Task 2.1

## 📦 Manual Deployment

> **Private S3 Deployment URL**  
> _(Requires access via CloudFront)_

🔗 [https://d2xxyi4mwb6is6.cloudfront.net/](https://d2xxyi4mwb6is6.cloudfront.net/)

---

# ⚡ Task 2.2

## 🤖 Automated Deployment

> **Deployed CloudFront URL**

🔗 [https://d1baeafe5g0fnf.cloudfront.net](https://d1baeafe5g0fnf.cloudfront.net)

## 🛠️ Scripts & Deployment

### 🚀 Build and Deploy

To build and deploy the frontend and infrastructure:

1. Open a terminal in the `infra` directory.
2. Run:

   ```sh
   npm run deploy
   ```

   This command will:

   - Build the frontend
   - Upload it to S3
   - Invalidate the CloudFront cache automatically

---

### 📋 Additional Scripts

- `npm run build` – Build the frontend and infrastructure code only
- `npm run synth` – Synthesize the CloudFormation template
- `npm run destroy` – Remove the deployed stack from AWS
