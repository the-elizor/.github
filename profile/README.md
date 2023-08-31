# Elizor Ecommerce Platform Project

Welcome to the official GitHub repository for Elizor, an online ecommerce platform aimed at bridging the gap between local communities and small vendors, especially in light of the COVID-19 restrictions. This project was initiated by Elizor Pvt Ltd, registered on December 19, 2019. As Elizor, our primary goal is to establish meaningful connections between locals and their neighborhood markets. To this end, we have introduced innovative concepts that enhance the shopping experience.

- **Elizor GO:** Recognizing the importance of localized markets, we've introduced the concept of Elizor GO. This initiative aims to facilitate easy access to neighborhood retailers, fostering a sense of community and supporting local businesses.

- **Elizor Fresh:** Beyond traditional products, we're pleased to offer fresh produce, including vegetables, fruits, and meats, through Elizor Fresh. This extension empowers customers to access quality, locally-sourced goods, promoting healthy living and supporting local farmers.

- **Elizor Bulk:** For those seeking larger quantities, Elizor Bulk offers a solution. We provide bulk products under this banner, allowing customers to purchase any amount they need, exceeding a minimum limit. This flexible approach caters to both individuals and businesses.

## Project Overview

Elizor's primary objective is to provide a seamless shopping experience for customers who are unable to physically visit small vendors and markets due to the ongoing COVID-19 pandemic. To achieve this, we followed the Software Development Life Cycle (SDLC) methodology to gather requirements and create an efficient solution.

## Gathering Requirements

Given the constraints posed by the pandemic, we focused our efforts on serving customers in the nearest cities as a beta testing phase. The journey began with the collection of valuable information from these communities, helping us better understand their needs and preferences.

## Logo

Here's the logo that symbolizes the essence of Elizor:
![Elizor Logo]()

## Development Approach

We adopted Scrum practices to ensure a well-structured development process. Our methodology included daily standup meetings, maintaining user stories, sprint planning for 10-day cycles, and thorough sprint reviews.

## Architecture

Elizor's architecture was thoughtfully designed to provide a robust and scalable foundation. We meticulously evaluated different cloud providers, including AWS, Azure, and Google Cloud, ultimately choosing AWS. The architecture diagram is as follows:
![Architecture Diagram](link-to-your-architecture-image)

For scalability and cost-efficiency, we opted for a serverless architecture using AWS. We utilized AWS AppSync with GraphQL queries for the backend and AWS Amplify as our build manager. Various AWS services played crucial roles, such as:
- Amazon S3 for storing product and customer images
- Amazon CloudFront for content delivery
- AWS Identity and Access Management (IAM) for access control
- Amazon DynamoDB for product storage
- Amazon Elasticsearch for enhanced search functionality
- AWS Lambda for image uploads and customer reviews
- Amazon Route 53 for DNS management

## Frontend

Elizor's frontend is built using the Angular framework for both the public ecommerce site and the admin app. We ensured a clear and organized component structure, enhancing maintainability and readability. Here's an overview of the Angular component structure:
![Angular Component Structure](link-to-your-component-structure-image)

## Features

- **Delivery Options:** We offer customers three distinct delivery choices, including one-day delivery and free delivery.
- **Payment Methods:** Our checkout process is supported by various payment methods, including Visa, MasterCard, and bank transfers. We integrated the Payhere third-party gateway to facilitate payments securely.

## Screenshots

Here are some screenshots showcasing different aspects of the Elizor Ecommerce Platform:

- **Home Page:**
  Welcome to Elizor's homepage, where customers can explore a wide range of products.
  <img alt="Home page image" src="https://github.com/the-elizor/.github/raw/main/screenshots/home-page.png">

- **Category Page:**
  Discover products organized by categories for a convenient shopping experience.
  <img alt="Category page image" src="https://github.com/the-elizor/.github/raw/main/screenshots/category-page.png">

- **Product Detail Page:**
  Detailed information about a selected product, including images, specifications, and customer reviews.
  <img alt="Product detail page image" src="https://github.com/the-elizor/.github/raw/main/screenshots/product%20details%20page.png">

- **Search Result for "Chocolate":**
  Search results for the term "Chocolate," displaying relevant products.
  <img alt="Search result for Chocolate image" src="https://github.com/the-elizor/.github/raw/main/screenshots/search-results-for-chocolate.png">

- **Cart Page:**
  Review and manage your selected products before proceeding to checkout.
  <img alt="Cart page image" src="https://github.com/the-elizor/.github/raw/main/screenshots/cart-screen.png">

- **Delivery Options in Checkout:**
  Choose from different delivery options to suit your preferences.
  <img alt="Delivery options in checkout image" src="https://github.com/the-elizor/.github/raw/main/screenshots/delivery-options.png">

- **Payment Methods in Checkout:**
  Select a convenient payment method for your order.
  <img alt="Payment methods in checkout image" src="https://github.com/the-elizor/.github/raw/main/screenshots/payment-methods.png">

- **New Address Addition:**
  Easily add a new address and set it as the default for future orders.
  <img alt="New address addition image" src="https://github.com/the-elizor/.github/raw/main/screenshots/add-new-address.png">

- **Featured Products:**
  Explore featured products that are currently in the spotlight.
  <img alt="Featured products image" src="https://github.com/the-elizor/.github/raw/main/screenshots/featured-page.png">


## Marketing and Promotion

To promote Elizor and engage with the community, we maintained active social media profiles on Facebook and Instagram. Several successful marketing campaigns were run, resulting in increased visibility and engagement. Here are some of the marketing banners we created:
  <img alt="Marketing banners" src="https://github.com/the-elizor/.github/raw/main/marketing/132005548_116403713659225_1258443222430492776_n.jpg">
  <img alt="Marketing banners" src="https://github.com/the-elizor/.github/raw/main/marketing/182605468_23847550076670297_4455096076368233450_n.jpg">
  <img alt="Marketing banners" src="https://github.com/the-elizor/.github/raw/main/marketing/183450200_193256082640654_1785580021906135180_n.jpg">
  <img alt="Marketing banners" src="https://github.com/the-elizor/.github/raw/main/marketing/184621686_194194655880130_4041770494901638264_n.jpg">

## Roadmap

We have an exciting roadmap ahead, with plans to implement the following features:
- **Save and Subscribe** Introducing a subscription model for frequent customers to simplify repeat purchases.
- **Seller Registration:** Allowing sellers to register with multiple locations.
- **Customized User Experience:** Enabling customers to select their location for a tailored view of available products and inventory management.

Thank you for exploring the Elizor Ecommerce Platform Project! We're excited about the journey ahead as we continue to enhance the platform and cater to the evolving needs of our customers and partners. Your feedback and contributions are greatly appreciated.
