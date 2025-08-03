# 🛒 MegaMyanmar — GrandNode E-Commerce Store

A modern, feature-rich, and scalable eCommerce platform built with GrandNode (ASP.NET Core + MongoDB). Designed for rapid customization, SEO optimization, and mobile-first responsiveness, MegaMyanmar offers a branch of Myanmar food import from Myanmar for Kiwin Myanmar people in New Zealand.

I will also be releasing a simplified eCommerce version soon, specifically designed for ASP.NET Core junior developers, using N-Tier architecture with MySQL as the database. Since it is built on Entity Framework, you can easily switch to any supported database provider. For this project, I chose MySQL to accommodate the needs of my client. 
Front End User Screenshots
![MegaMyanmar Screenshot](https://raw.githubusercontent.com/maxzaw83/maxzaw/refs/heads/main/public/images/s1.jpg)
(https://raw.githubusercontent.com/maxzaw83/maxzaw/refs/heads/main/public/images/s2.jpg)
(https://raw.githubusercontent.com/maxzaw83/maxzaw/refs/heads/main/public/images/s2.jpg)


Backend Admin Screenshots
(https://raw.githubusercontent.com/maxzaw83/maxzaw/refs/heads/main/public/images/a1.jpg)
(https://raw.githubusercontent.com/maxzaw83/maxzaw/refs/heads/main/public/images/a2.jpg)


## 🚀 Key Features

- 🧱 Built on **GrandNode 2.3** (ASP.NET Core & MongoDB)
- 🎨 Fully responsive UI with Bootstrap and jQuery
- 🛍️ Product catalog, variants, reviews, and filters
- 📦 Inventory & order management
- 💳 Stripe, PayPal, and offline payment options
- 🔒 Role-based access (Admin, Vendor, Customer)
- 🌐 SEO & multi-language support
- 📤 Deployed on Azure (App Service + MongoDB Atlas)

## 💻 Tech Stack

- **Backend**: ASP.NET Core, C#, GrandNode
- **Database**: MongoDB
- **Frontend**: Bootstrap, jQuery, Razor Views
- **DevOps**: GitHub, Docker, Azure DevOps (CI/CD)
- **Hosting**: Azure App Service, MongoDB Atlas

## 📦 Getting Started

### Prerequisites

- [.NET SDK 8.0+](https://dotnet.microsoft.com/)
- [MongoDB 6.0+](https://www.mongodb.com/)
- Node.js (optional, for assets bundling)

### Installation

```bash
git clone https://github.com/maxzaw83/megamyanmar-grandnode.git
cd megamyanmar-grandnode

# Restore and build the solution
dotnet restore
dotnet build

# Start the GrandNode store
dotnet run --project GrandNode.Web
🛠 Configuration
All settings can be modified via the Admin Dashboard (e.g., payment, shipping, SEO, etc.).

Default admin credentials:

Email: admin@yourstore.com

Password: admin

⚠️ Remember to change admin credentials after first login.

✨ Customization
You can override themes and UI elements via:

Themes/MegaMyanmar/Views/

wwwroot/css/ and wwwroot/js/

Razor partials and layouts under Views/Shared/

📤 Deployment
Recommended (Azure + MongoDB Atlas)
Set ConnectionString in appsettings.json

Use dotnet publish to generate deployment assets

Deploy to Azure App Service or your preferred host

🧪 Testing
Use Swagger UI for API endpoints: http://localhost:5000/swagger

Implement integration tests using xUnit or NUnit

📚 Documentation
For detailed configuration and extension guides, refer to:

GrandNode Docs

MongoDB Atlas Docs

ASP.NET Core Docs

📜 License
This project is open-sourced under the MIT License.

📣 Credits
GrandNode

Bootstrap

MongoDB

Azure

🙌 Want to Contribute?
Feel free to fork the repo, submit PRs, or request features. If you use this project commercially, attribution is appreciated.

⭐ Like it?
Star ⭐ the repository to show support and help it reach more developers.
