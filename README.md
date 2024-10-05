# **Real Estate Investment Analysis in Madrid**

This report presents key insights from an exploratory analysis using Airbnb rental data from [Inside Airbnb](https://insideairbnb.com/get-the-data/). The primary objective is to provide strategic information to guide real estate investment opportunities in Madrid, with a focus on short-term rental markets.

The complete analysis can be found in the Python notebooks.

## **Context**

Madrid was selected as the target city for real estate investment with the aim of generating income through short-term rentals. An exploratory analysis was conducted to guide the valuation team in their search for investment opportunities. Since the database does not provide property purchase prices, we estimated prices using the following assumptions:

- 1 bedroom: 60 m²
- 2 bedrooms: 70 m²
- 3 bedrooms: 90 m²
- 4 bedrooms: 120 m²
- 5+ bedrooms: 150 m²

These estimates were multiplied by the price per square meter for each district (data from Idealista). The analysis was conducted using **Python**.

## **Objectives**

- Analyze public data sources to understand the real estate market in Madrid.
- Identify strategic insights to guide investment opportunities.
- Focus on key aspects such as rental price per night, occupancy levels, and property purchase prices.

## **Key Findings**

- Identified several districts with high investment potential.
- Properties suitable for 3 guests are the most profitable.
- Proximity to tourist attractions is not a key factor in the identified districts.
- Explore developing rental products for sporting events in the San Blas district.

## **Main Results**

### 1. 12 Districts with High Investment Potential

We identified districts that offer a favorable cost-income ratio for real estate investment. These districts were grouped by property quality:

**Low**: San Andrés, San Diego, Opañel  
**Lower-Middle**: Hellín, Rosas, Simancas (likely in San Blas)  
**Middle**: Valdemarín, Atocha  
**Upper-Middle**: Jerónimos, El Viso  
**High**: Recoletos, Castellana  

![Rental Price by District](Precio_por_barrio.png)

### 2. Focus on 1-Bedroom Properties for 3 Guests

Properties that accommodate 3 guests are optimal. There is little difference in profitability between 0-3 guests, but for properties accommodating 5 or more, the property size and purchase price increase significantly.

![Price by Guest](Precio_por_huesped.png)

### 3. Proximity to Attractions is Not Crucial

Proximity to major tourist attractions (e.g., Puerta del Sol) does not significantly impact rental prices in the identified districts.

![Distance to Puerta del Sol](Distancia_a_sol.png)

### 4. Potential for Sports Event Rentals in San Blas

Explore opportunities in San Blas, where many properties are not yet capitalizing on the demand for sports-related rentals near the Wanda Metropolitano Stadium.

![San Blas Rentals](Distancia_Wanda_Metropolitano.png)

**Price Legend (Low to High)**:  
Purple - Blue - Orange - Red

The map shows the average rental price in San Blas, with colors representing price ranges. The large number of purple and blue points indicates untapped potential for sports-event-related rentals near Wanda Metropolitano Stadium.

## **Disclaimer**

This project does not provide investment recommendations. The results and conclusions are based on data analysis and should be interpreted with caution.











