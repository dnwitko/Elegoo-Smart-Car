# Elegoo-Smart-Car

This project deploys low-latency computer vision and voice recognition models on the ESP32-S3-EYE module to control an Elegoo AI-powered robot car. Using Google’s Teachable Machine, the system trains and tests models for recognizing visual and auditory inputs. The ESP32-S3-EYE microcontroller supports machine learning inference while operating under strict memory and processing constraints. This project utilizes Lite Runtime (LiteRT), a framework which allows machine learning to be deployed on edge devices with small memory and processing power to optimize performance. It is hypothesized that LiteRT will reduce inference latency and improve responsiveness, demonstrating the feasibility of deploying AI on resource-constrained devices for robotics and smart home applications. This is my University Research Symposium Project for 2025. 

# Hardware Requirements
- [Elegoo Smart Car Robot](https://us.elegoo.com/products/elegoo-smart-robot-car-kit-v-4-0)
- [ESP32-S3-EYE Dev Board](https://www.aliexpress.us/item/3256803794751194.html)
- [CP2102 Micro USB to UART Converter](https://www.amazon.com/HiLetgo-CP2102-Module-Converter-Replace/dp/B01N47LXRA)
- [JST XH to Dupont Connector Kit](https://www.amazon.com/Kidisoii-Dupont2-54-Connector-Pre-Crimped-Compatible/dp/B0CMCN9CXD/135-4941321-1839956)
- [Micro USB to Micro USB Male-to-Male OTG Cable](https://www.amazon.com/Micro-USB-Male-Data-Cable/dp/B0872GMD7V/)
- USB-C to Micro USB Cable
