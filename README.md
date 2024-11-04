# Ecolens

Ecolens is an application that helps companies estimate and report on their greenhouse gas emissions following the [Greenhouse Gas (GHG) Protocol](https://ghgprotocol.org/). My aim is to address a key need in sustainable reporting with the growing pressure of regulation on global emissions.

## Greenhouse Gas Protocol breaks down the emission into 3 scopes

1. Direct emissions from owned or controlled sources (e.g., company vehicles, on-site fuel combustion).
2. Indirect emissions from purchased electricity, steam, heating, and cooling.
3. All other indirect emissions across the value chain (e.g., purchased goods, waste, employee commuting, etc.).

## Features

1. **Emission Calculator Based on the GHG Protocol**
The application guides companies to calculate emission by each scope, starting with scope 1 and 2, which are often easier to quantify, and offering more detailed options for scope 3 if they want to expand.
2. **Modular Data Collection**
The companies can choose which scope and activities to track based on their available data and goals. This could help them start small (e.g., just Scopes 1 and 2) and then gradually incorporate Scope 3 as they gather more data. The application provides common categories (e.g., business travel, waste generation, or product use phase, etc.) so companies can input rough estimates if they lack exact figures.
3. **Built-In Emissions Factors Database**
The application uses data from reputable databases for emission factors (e.g., kg CO2e per unit of fuel burned, per kWh of electricity, etc.) tailored to specific activities or regions,  allowing for a more precise calculation.
4. **Reporting and Compliance Tools**
After giving enough data the company can choose to generate reports that aligns with a framework like CDP ((Carbon Disclosure Project)[https://www.cdp.net/en/companies/reporter-services/reporter-services-comparative-analysis]). This helps companies to use these reports directly for their sustainability disclosures.
They also able to provide automatic summaries of emissions by scope and allow users to create customised reports for stakeholders, helping companies align with GHG reporting standards.
5. **Benchmarking and Comparison**
Companies have the ability to benchmark their emissions against industry standards or historical data, so they can see how their footprint stacks up and track improvements over time. This can help companies see trends and set realistic goals for emission reduction.
6. **Scenario Planning**
A scenario analysis tool exists that helps businesses see how potential changes (e.g., switching to renewable energy, reducing travel) could impact their emissions. This can serve as a decision-making aid for setting and meeting reduction targets.

# Used technologies

- **Frontend**: HTML, CSS, TypeScript
- **Backend**: Laravel
- **Database**: MySQL
- **Other**: Vite
