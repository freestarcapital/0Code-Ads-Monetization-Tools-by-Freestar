# 0Code - Freestar Monetization Google Tag Manager Template

# Freestar Ad Tag Template for Website Monetization

## Overview

The **Freestar Ad Tag Template** is a no-code solution designed to simplify the integration of Freestar’s ad technology for publishers using **Google Tag Manager (GTM)**. This template allows publishers to deploy Freestar ad tags seamlessly without having to manually insert the code into the `<head>` of their website.

With this template, publishers can instantly monetize their websites by leveraging Freestar’s industry-leading ad optimization technology, reducing the time and effort required to configure ad tags manually. It is particularly useful for publishers with limited engineering resources who are looking for an efficient and streamlined monetization setup.

## Features

- **Zero Coding Required**: Deploy the template directly from GTM, without needing developer support.
- **Seamless Ad Integration**: Insert Freestar ad tags directly into your site, ensuring faster ad loading and higher monetization potential.
- **Customizable Ad Placements**: Easily configure and manage ad slots using Google Tag Manager’s interface.
- **Supports First-Party Data**: Leverage first-party data and key-value targeting for better ad performance.
- **Flexible Triggering**: Use GTM triggers to control when and where ads are loaded on your site.

## How It Works

The Freestar Ad Tag Template simplifies ad deployment by allowing publishers to:

1. Install the template in **Google Tag Manager**.
2. Configure the necessary ad slots within GTM.
3. Automatically load and serve Freestar ads on all pages without the need for manual `<head>` code insertion.

## Installation

1. **Import the Template**:
   - Download the JSON file from this repository.
   - Log in to your **Google Tag Manager** account and navigate to the desired container.
   - Click on **Admin** > **Import Container**.
   - Upload the JSON file, select **Merge** (to avoid overwriting existing tags), and follow the prompts to complete the import process.

2. **Configure Ad Slots**:
   - After importing the template, configure the ad slots in GTM by entering the appropriate slot IDs provided by Freestar in the tag configuration.
   - Use GTM’s **Triggers** to control when and where the ads are served.

3. **Preview and Publish**:
   - Test your configuration using GTM’s **Preview** mode.
   - Once the setup is confirmed to be working, publish the changes to your live site.

## Requirements

- A valid **Freestar publisher ID**.
- A working **Google Tag Manager** container.
- Basic familiarity with GTM for setting up triggers and testing.

## Usage

Once installed and configured, the Freestar Ad Tag Template will automatically load Freestar ads across the pages of your site based on the trigger conditions set in GTM. You can configure multiple ad units and set specific targeting parameters as needed.

### Template Parameters

- **Publisher ID**: The unique identifier provided by Freestar for your account.
- **Ad Slot IDs**: The IDs for the ad placements on your site.
- **Key-Value Pairs**: Optional parameters for advanced ad targeting.

### Example

```js
{
  "publisher_id": "123456789",
  "ad_slots": ["ad-slot-1", "ad-slot-2"],
  "key_value_pairs": {
    "category": "technology",
    "user_type": "new_visitor"
  }
}
