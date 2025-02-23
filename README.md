Wazuh 4.x Single-Node Setup Automation
Automate the deployment of a robust, single-node Wazuh 4.x environment with ease! This script handles the heavy lifting, setting up Wazuh’s powerful security monitoring and threat detection system with SSL encryption, customized configurations, and seamless service initialization. Perfect for security teams looking to quickly deploy a fully functional Wazuh instance on a single node.

Features 🚀
Effortless SSL Certificate Generation
Secure your Wazuh communications with auto-generated SSL certificates. No manual intervention needed; the script ensures end-to-end encryption for all components.

Automated Component Configuration
Set up Wazuh Indexer, Manager, and Dashboard to work harmoniously. The script configures config.yml and opensearch.yml with custom IPs and predefined security settings, ensuring consistency and reliability.

Filebeat Setup for Efficient Log Management
Automatically installs and configures Filebeat to collect and forward logs, enabling real-time monitoring and alerting with minimal effort.

Streamlined Service Management
Starts and enables essential Wazuh services (Indexer, Manager, Filebeat, and Dashboard) automatically. Just run the script, and your environment is live and ready to monitor threats!

Customizable API Integration
Configures Wazuh Dashboard with the Wazuh Manager API URL, allowing you to visualize alerts and data insights instantly.

Why Use This Script? 💡
Setting up Wazuh can be a complex and time-consuming process, especially if done manually. This script takes care of every detail, allowing you to focus on what really matters—securing your environment. Whether you're an experienced DevOps engineer or new to Wazuh, this automation script provides a repeatable, reliable, and secure setup in just minutes.

What's Included? 📦
config.yml: Customizes Wazuh nodes with user-defined IPs.
opensearch.yml: Configures Wazuh Indexer with SSL and security settings.
Filebeat Configuration: Sets up Filebeat to integrate seamlessly with Wazuh.
Service Management: Enables and starts all Wazuh services for instant functionality.
Benefits 🎉
Speed: Deploy a fully functional Wazuh setup in minutes.
Security: Automatic SSL certificate generation and deployment for secure communication.
Simplicity: No need to manually edit configurations—just enter the IP, and you're set.
Consistency: Ensures that every setup is the same, reducing potential errors and misconfigurations.
Troubleshooting 🛠️
If you encounter any issues during setup:

Check Logs: Look at the log files in /var/log/wazuh-* for detailed error messages.
Verify IP Configuration: Ensure the IP address entered matches your network setup.
Restart Services: Try restarting services if they fail to start initially.
Contributing 🤝
Contributions are welcome! Feel free to submit a pull request or report issues.

License 📜
This project is licensed under the MIT License.
