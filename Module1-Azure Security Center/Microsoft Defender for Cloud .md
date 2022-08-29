# Azure Security Center/ Microsoft Defender for Cloud
## Lab objectives
In this lab, you will complete the following exercise:

1. Exploring Microsoft Defender for Cloud 
2. Configure Security Policies 
3. Configure Azure inbuild policies definition for Microsoft Defender for cloud. 
4. Secure Score 
5. Improving your Secure Posture 
6. Exploring Security Center and Security benchmark 

### Exercise 1: Exploring Microsoft Defender for Cloud

# What is Microsoft Defender for Cloud?

Microsoft Defender for Cloud is a Cloud Security Posture Management (CSPM) and Cloud Workload Protection Platform (CWPP) for all of your Azure, on-premises, and multicloud (Amazon AWS and Google GCP) resources. Defender for Cloud fills three vital needs as you manage the security of your resources and workloads in the cloud and on-premises:

![image](https://user-images.githubusercontent.com/33771500/187170501-f78beb93-08d6-47f1-8fa7-bb8798b685a5.png)

- [**Defender for Cloud secure score**](secure-score-security-controls.md) **continually assesses** your security posture so you can track new security opportunities and precisely report on the progress of your security efforts.
- [**Defender for Cloud recommendations**](security-policy-concept.md) **secures** your workloads with step-by-step actions that protect your workloads from known security risks.
- [**Defender for Cloud alerts**](alerts-overview.md) **defends** your workloads in real-time so you can react immediately and prevent security events from developing.

Defender for Cloud secure score continually assesses your security posture so you can track new security opportunities and precisely report on the progress of your security efforts.
Defender for Cloud recommendations secures your workloads with step-by-step actions that protect your workloads from known security risks.
Defender for Cloud alerts defends your workloads in real-time so you can react immediately and prevent security events from developing.

# Task 1: Enable enhanced security features

**To enable enhanced security features on one subscription**:

1. Sign in to the [Azure portal](https://portal.azure.com).

1. Search for and select **Microsoft Defender for Cloud**.

1. From Defender for Cloud's main menu, select **Environment settings**.
    
1. Select the subscription or workspace that you want to protect.
    
1. Select **Enable all** to enable all of the plans for Defender for Cloud.

![image](https://user-images.githubusercontent.com/33771500/187176353-ad30eda1-d7bd-4616-a26f-7a1f1c1138ef.png)

1. Select Save.

**To enable enhanced security on multiple subscriptions or workspaces**:

1. Sign in to the [Azure portal](https://portal.azure.com).

1. Search for and select **Microsoft Defender for Cloud**.

1. From Defender for Cloud's menu, select **Getting started**.

    The Upgrade tab lists subscriptions and workspaces eligible for onboarding.

![image](https://user-images.githubusercontent.com/33771500/187176984-263f9f80-4e10-455b-b147-2e39f1e62551.png)

1. Select the desired subscriptions and workspace from the list.

1. Select Upgrade.

![image](https://user-images.githubusercontent.com/33771500/187177219-94434f88-95aa-4907-b289-d17872707b72.png)

## Customize plans

Certain plans allow you to customize your protection.

You can learn about the differences between the [Defender for Servers plans](defender-for-servers-introduction.md#defender-for-servers-plans) to help you choose which one you would like to apply to your subscription.

Defender for Databases allows you to [select which type of resources you want to protect](quickstart-enable-database-protections.md). You can learn about the different types of protections offered.

Defender for Containers is available on hybrid and multicloud environments. You can learn more about the [enablement process](defender-for-containers-enable.md) for Defender for Containers for each environment type.

## Disable enhanced security features

If you choose to disable the enhanced security features for a subscription, you'll just need to change the plan to **Off**.
 
**To disable enhanced security features**:

1. Sign in to the [Azure portal](https://portal.azure.com).

1. Search for and select **Microsoft Defender for Cloud**.

1. From Defender for Cloud's menu, select **Environment settings**.

1. Select the relevant subscriptions and workspaces.

1. Find the plan you wish to turn off and select **Off**.

![image](https://user-images.githubusercontent.com/33771500/187178351-ec9fa146-c368-4d3b-9b3d-bda09f773703.png)



