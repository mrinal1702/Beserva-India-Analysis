# Beserva India Analysis

This project is inspired by my good friend and fellow NYU alum, **Maria**, who founded [Beserva](https://www.beserva.com/) — a Mexico City–based startup building a **WhatsApp-integrated LLM bot** for salons and beauty parlors.  
Beserva’s product helps small businesses manage **appointments, scheduling, and cancellations**, reducing missed bookings due to admin problems. It’s especially impactful in markets where **WhatsApp is the dominant communication channel**.

---

## 🎯 Project Goal

The goal of this project is two-fold:

1. **Market relevance in India**  
   Can we prove that India — and specifically Mumbai — faces scheduling/admin problems that Beserva can solve?  

2. **Impact on businesses**  
   Can we show, using data, how deep these problems are and whether they disproportionately affect **lower-rated businesses** compared to higher-rated ones?

---

## 📊 Data Collection

Data was collected using the **Google Places API**.  
- I scraped reviews from **360 businesses in Mumbai**, identified through the following queries:

"beauty salon in Mumbai",
"hair salon in Mumbai",
"spa in Mumbai",
"makeup studio in Mumbai",
"beauty parlour in mumbai",
"hairdresser in mumbai",
"barbershop in mumbai",
"nail salon in mumbai",
"pedicure in mumbai",
"manicure in mumbai",
"nail salon in Mumbai"


- For each business, the API provides **up to 5 “most relevant” reviews**.  
  This is a **limitation of the free API** — in practice, one can obtain **all reviews for all places** through advanced pipelines or third-party datasets (likely paid).  
- Despite this limitation, the dataset still provides **1,000+ reviews** with enough signal to analyze scheduling/admin issues in Mumbai’s salon ecosystem.

---

(👉 Next sections will cover **analysis**, **results**, and **insights** once we move further.)
