# Notify-MDC-Reco-MailTeams
> This playbook will notify Microsoft Defender for Cloud Security Recommendation to Email and Microsoft Teams.

このレポジトリは Azure リソースのリソースタグ (Owner) を取得し、以下を行います。
- Owner で指定したメールアドレスに通知
  - Owner タグが無い場合は、グループメールアドレスに通知
- Microsoft Teams チャネルに通知
  - 指定したチャネル宛に Adaptive Card Format で通知

# 通知イメージ
> Here is a Email / Teams image

- Email
![image](https://github.com/user-attachments/assets/fa00b0f4-f841-4e70-93af-a9ce8fef3839)

- Microsoft Teams
![image](https://github.com/user-attachments/assets/9e54b6b8-83c2-4669-abe2-52b40dc49dfe)

# Deploy To Azure
> Push to Deploy to Azure

