# TN-Solar ☀️

## Solar Lighting Products Catalogue

Welcome to the **TN-Solar** product catalogue repository.

TN-Solar provides a range of **solar-powered lighting products** suitable for residential, commercial, industrial, outdoor and street-lighting applications.

This repository contains the structured product catalogue, product specifications, pricing information and product images used by TN-Solar's website and digital catalogue.

---

## 📦 Product Categories

The catalogue is organized into the following product categories:

1. **Solar Street Light - ABS Plastic**
2. **Solar Street Light - Semi Integrated Model**
3. **Solar Street Light - Mettalic**
4. **Solar Project Street Lights**
5. **Solar UFO Lamp**
6. **Solar Bill Board Lamp**
7. **Solar Pillar Lamp**
8. **Solar Bollard Lamp**
9. **Solar Wall Lamp**
10. **Solar Flood Lamp**
11. **Solar Ceiling Lamp**
12. **Solar Motion Sensor Lamp**
13. **Solar Road Studs**
14. **Solar Decoration Lamp**
15. **Street Light and UFO - Poles**

The current catalogue contains **85 products across 15 categories**.

---

## 📁 Repository Structure

```text
tn-solar/
│
├── data/
│   └── hardoll_price_catalogue_by_category.json
│
├── images/
│   ├── SSL-ABS-50W.png
│   ├── SSL-ABS-100W.png
│   ├── SSL-ABS-150W.png
│   ├── SSL-INT-200W.png
│   ├── SGL-UFO-300W-SQ.png
│   └── ...
│
├── index.html
├── css/
│   └── style.css
│
├── js/
│   └── app.js
│
└── README.md
```

---

## 🗂️ Product Data

Product information is maintained in JSON format.

Each product contains:

```json
{
  "Model": "SSL-ABS-50W",
  "Name": "SOLAR STREET LIGHT",
  "Specifications": "...",
  "MRP": 1510,
  "Wholesale Price": 878,
  "Sample Price": 922,
  "Image": "SSL-ABS-50W.png",
  "Source Page": 1
}
```

### Available Product Information

* **Model**
* **Product Name**
* **Specifications**
* **MRP**
* **Wholesale Price**
* **Sample Price**
* **Product Image**
* **Source Page**

---

## 🖼️ Product Images

Each product image is stored using its **Model Number** as the filename.

For example:

```text
SSL-ABS-50W.png
SSL-ABS-100W.png
SSL-ABS-150W.png
SSL-ABS-300W.png
SSL-INT-200W.png
SSL-PRO-50W.png
SGL-UFO-300W-SQ.png
SBBL-40W.png
SPL-25W-SQ.png
```

Using the model number as the filename ensures that every product image can be uniquely associated with its product data.

---

## 🌞 Solar Lighting Range

TN-Solar's current catalogue includes products such as:

* Solar Street Lights
* Solar Project Street Lights
* Solar UFO Garden Lights
* Solar Bill Board Lights
* Solar Pillar Lamps
* Solar Bollard Lamps
* Solar Wall Lamps
* Solar Flood Lamps
* Solar Ceiling Lamps
* Solar Motion Sensor Lamps
* Solar Road Studs
* Solar Decoration Lamps
* Solar Lighting Poles and Accessories

---

## 💰 Pricing

The catalogue contains:

| Price Type          | Description                            |
| ------------------- | -------------------------------------- |
| **MRP**             | Maximum Retail Price                   |
| **Wholesale Price** | Wholesale price shown in the catalogue |
| **Sample Price**    | Sample price shown in the catalogue    |

Prices are maintained in **Indian Rupees (₹)**.

> **Note:** Prices may change. The JSON data should be treated as the current catalogue data provided to TN-Solar and should be updated whenever a revised price catalogue is received.

---

## 🧩 Website Integration

The JSON structure is designed to make it easy to build a dynamic product catalogue.

The website can:

1. Load the JSON file.
2. Display all product categories.
3. Display products under each category.
4. Load the corresponding product image automatically.
5. Display specifications and pricing.
6. Create individual product cards.
7. Create category-wise product listings.
8. Add search and filtering functionality.
9. Add WhatsApp enquiry/order functionality.

Example:

```text
Solar Street Light - ABS Plastic
│
├── SSL-ABS-50W
├── SSL-ABS-100W
├── SSL-ABS-150W
├── SSL-ABS-300W
├── SSL-ABS-400W
├── SSL-ABS-500W
└── SSL-ABS-600W
```

---

## 🔍 Recommended Product URL Structure

For a future website, product URLs can follow a simple model-based structure:

```text
/products/SSL-ABS-50W
/products/SSL-ABS-100W
/products/SSL-INT-200W
/products/SGL-UFO-300W-SQ
```

This makes the product catalogue easy to navigate and maintain.

---

## 📱 Mobile-First Catalogue

The TN-Solar catalogue is intended to be **mobile-friendly and responsive**, allowing customers to browse products easily from:

* 📱 Mobile phones
* 💻 Desktop computers
* 📲 Tablets

Product cards should prominently display:

**Product Image → Model → Name → Key Specifications → Price → Enquiry**

---

## 📞 Customer Enquiry

The catalogue can be integrated with WhatsApp or other communication channels so customers can directly enquire about a product using its model number.

Example:

```text
Hello TN-Solar,

I am interested in:

Model: SSL-ABS-100W
Product: Solar Street Light

Please share the availability and latest price.
```

---

## 🔄 Catalogue Updates

When a new distributor price catalogue is received:

1. Extract the product information.
2. Identify category headings.
3. Update the JSON catalogue.
4. Add or replace product images.
5. Verify Model Numbers.
6. Verify MRP.
7. Verify Wholesale Price.
8. Verify Sample Price.
9. Commit the updated files to GitHub.

This keeps the website catalogue synchronized with the latest product information.

---

## 📊 Current Catalogue

**Total Categories:** 15

**Total Products:** 85

**Product Images:** Model-number based PNG files

**Data Format:** JSON

**Currency:** INR (₹)

---

## ⚠️ Important

Product specifications, prices, availability and other catalogue information should always be verified against the latest official price catalogue before placing an order.

The information in this repository is intended for **TN-Solar's digital product catalogue and website presentation**.

---

## 🚀 Future Enhancements

Possible future additions include:

* Product search
* Category filtering
* Product comparison
* WhatsApp enquiry
* Online quotation request
* Shopping cart
* Customer registration
* Dealer login
* Stock availability
* Automatic price updates
* Product PDF generation
* SEO-friendly product pages
* Product sharing on WhatsApp
* PWA/mobile application support

---

## 📄 Data Source

The current product information has been structured from the **Hardoll Enterprises LLP Distributor Price List** supplied for the TN-Solar catalogue. The catalogue itself identifies the product columns as Picture, Model, Name, Specifications, MRP and pricing information.

---

## © TN-Solar

**TN-Solar – Solar Lighting Solutions**

A digital catalogue for solar lighting products and solutions.
