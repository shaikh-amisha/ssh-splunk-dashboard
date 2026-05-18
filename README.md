# 🛡️ SSH Dashboard Using Splunk

The SSH Logs Monitoring Dashboard is a security monitoring solution developed using **Splunk Enterprise** to analyze and visualize SSH authentication logs from Linux systems. The dashboard helps detect suspicious login activity, failed authentication attempts, brute-force attacks, and unauthorized SSH access attempts in real time.

This project demonstrates practical **SIEM implementation**, **log analysis**, **threat detection**, and **security monitoring skills** commonly used in **SOC (Security Operations Center)** environments.

---

# 🚀 Features

✅ Real-time SSH log monitoring  
✅ Failed and successful login tracking  
✅ Detection of possible brute-force attacks  
✅ Username-based failed login analysis  
✅ Suspicious IP identification  
✅ Geo-location visualization of attack sources  

---

# 📊 Dashboard Panels

## 🔹 a. Total SSH Events
Displays the total number of SSH-related events collected during the selected time range.

---

## 🔹 b. Successful Logins
Shows the number of successful SSH authentications.

---

## 🔹 c. Failed Logins
Tracks failed authentication attempts to identify suspicious login activity.

---

## 🔹 d. Connections Without Authentication
Monitors incomplete or unauthenticated SSH connection attempts.

---

## 🔹 e. Failed Logins by Username
Visualizes usernames frequently targeted during failed login attempts.

---

## 🔹 f. Possible Brute Force Attacks
Identifies IP addresses generating excessive failed login attempts.

---

## 🔹 g. Geo-Location Attack Visualization
Displays the geographic origin of suspicious SSH activity using map visualization.

---

# DASHBOARD PREVIEW
![SSH Dashboard](./Splunk%20Dashboard.png)

---

# 🎯 Conclusion

This project demonstrates how **Splunk Enterprise** can be used to build an effective SSH security monitoring solution for detecting authentication-based threats and improving visibility into Linux server activities.

The dashboard provides actionable insights that help security analysts identify suspicious behavior and respond to potential security incidents efficiently.


