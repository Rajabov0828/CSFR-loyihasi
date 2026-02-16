3. Go to http://localhost:8080  
Login: admin / password  
Navigate to CSRF section and select security level  
4. Use buttons in demo.html for live demo  

### Test Results
- **Low**: No protection — attack successful (password changed)  
- **Medium**: Referer check — attack blocked  
- **High**: Anti-CSRF token — "Invalid CSRF token" error if token missing  

### Protection Methods
- Synchronizer Token Pattern (most effective)  
- SameSite Cookies (Strict/Lax)  
- Referer Header Validation  
- Re-authentication for critical actions  

### Sources
- DVWA: https://github.com/digininja/DVWA  
- Bootstrap: https://getbootstrap.com  
- GitHub Pages: https://pages.github.com  

Questions? Contact @Jurabek1603
Project completed in February 2026.
