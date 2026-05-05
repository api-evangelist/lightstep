---
title: "Has Anyone Automated Application Deployment Using ServiceNow Catalog Items?"
url: "https://www.servicenow.com/community/cloud-observability-forum/has-anyone-automated-application-deployment-using-servicenow/m-p/3399679#M24"
date: "Tue, 07 Oct 2025 10:10:11 GMT"
author: "Sravani36"
feed_url: "https://www.servicenow.com/community/s/cgfwn76974/rss/Category?category.id=cloud-observability&interaction.style=forum"
---
<p>Hi all,</p><p>I’m working on automating application deployment using a ServiceNow catalog item.</p><p>The goal is to allow developers to trigger deployments through a ServiceNow form, which collects inputs like:</p><ul><li>Application name and environment (Dev/QA/Prod)</li><li>Git repository details (URL, branch)</li><li>Deployment type (containerized, Helm chart, etc.)</li><li>CI/CD pipeline info (Jenkins, ArgoCD)</li><li>Environment variables and secrets</li></ul><p>Once submitted, the catalog item should trigger workflows (via Flow Designer or integrations) to deploy the application to pre-provisioned environments.</p><p>&nbsp;I’m looking for:</p><ul><li>Examples of similar implementations</li><li>Best practices for catalog item design</li><li>Tips on integrating with Jenkins, Git, ArgoCD</li><li>Handling secrets and approvals</li></ul><p>If anyone has done this or has resources to share, I’d love to learn from your experience!</p><p>&nbsp;</p><p>Thanks in advance <span class="lia-unicode-emoji" title=":raising_hands:">🙌</span></p>
