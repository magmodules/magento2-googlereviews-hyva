
![magento-google-hyva](https://github.com/magmodules/magento2-googlereviews-hyva-dev/assets/24823946/7db96cbc-bd57-49d4-819e-720a5d58eb73)



# Google reviews Hyvä Compatibility plugin


The Google Review plugin for Magento, compatible with the Hyvä theme, is a powerful integration that seamlessly connects the popular platform, Google, with Magento. This plugin offers extensive functionality to enhance your online store's reputation management and customer feedback process while ensuring smooth compatibility with the Hyvä theme.


The Google Review Hyvä Compatibility plugin for the Magento Hyva theme has the following requirements:
- [Magento 2.4.+](https://github.com/magento/magento2)
- [Hyvä](https://github.com/hyva-themes)
- [Magmodules Google Reviews](https://www.magmodules.eu/magento2-google-reviews.html)    

<img width="892" alt="magento-google-reviews" src="https://github.com/magmodules/magento2-googlereviews-hyva-dev/assets/24823946/12fc4545-dde5-4971-9130-6825a7e07998">


## About the Google Review Plugin

With the Google Review plugin, you can effortlessly integrate the review system into your Magento store, even if you are using the Hyva theme. This plugin ensures a smooth and seamless user experience, preserving the aesthetic and functionality of the Hyva theme while incorporating the Google Review system.

By utilizing this plugin, you can effectively collect and showcase customer reviews, ratings, and testimonials on your Magento website. It empowers you to display social proof, build trust with potential customers, and enhance your brand reputation. The integration allows customers to submit reviews, while also providing you with the necessary tools to moderate and manage the reviews within your Magento admin panel.

Moreover, the Google Review plugin offers advanced features such as automatic review requests, email notifications, customizable review widgets, and rich snippet integration for search engine optimization (SEO) benefits. These features enable you to actively engage with customers, gather valuable feedback, and enhance the overall shopping experience on your Magento store.

Overall, the Google Review plugin for Magento, with its seamless compatibility with the Magento Hyva theme, provides an excellent solution for integrating the Google Review platform into your online store. It helps you leverage customer reviews to boost credibility, enhance customer trust, and drive conversions.
## Installation

1. Install the module using composer: 

```bash
composer require magmodules/magento2-hyva-googlereviews
```

2. Enable the module:

```bash
bin/magento module:enable Magmodules_HyvaGoogleReviewsSR
```

3. Upgrade the database:

```bash
bin/magento setup:upgrade
```

4. Let Hyvä know about the new module:

```bash
php bin/magento hyva:config:generate
```

5. Generate the CSS files:

```bash
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run ci
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run build-prod
```

Or from your theme:

```bash
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run ci
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run build-prod
```

## Google Reviews Magento plugin features

- Seamless integration with Google
- Review collection automation
- Customizable review widgets
- Fully integrated in your Magento store
  
## Magento Support

If you have any questions, please fill out our secure contact form by clicking [here](https://www.magmodules.eu/support-form.html).

## Magmodules & Hyva

Magmodules and Hyva have established a strong partnership, working closely together to provide enhanced e-commerce solutions. As an official Hyva partner, we specializes in developing integrations for various platforms and services. 

We have created integrations for well-known providers such as Mollie, Sooqr, Paazl, and many more. This collaboration ensures seamless compatibility and optimized performance for online stores utilizing the Hyva theme. Through our partnership, Magmodules and Hyva strive to deliver comprehensive and tailored solutions to meet the diverse needs of e-commerce businesses.






## Checkout our other Hyva Plugins!

[- Magento 2 Hyvä Shopreview](#) 
 
[- Magento 2 Hyvä Product Review Reminder](#) 

[- Magento 2 Hyvä Mollie React Checkout](#) 

[- Magento 2 Hyvä Checkout](#) 

[- Magento 2 Hyvä Mollie React Checkout](#) 

[- Magento 2 Hyvä Paazl](#) 
