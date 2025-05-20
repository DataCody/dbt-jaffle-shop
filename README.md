## 🥪 dbt-jaffle-shop

A Modern Data Stack Project for End-to-End Analytics Engineering

This repository is a customized implementation of the [dbt-labs/jaffle-shop](https://github.com/dbt-labs/jaffle-shop) project, tailored to demonstrate proficiency in data modeling, testing, documentation, and orchestration using dbt. It serves as a comprehensive example of building a robust analytics pipeline from raw data ingestion to curated data marts.

## 🚀 Project Overview
- **Source Data**: Simulated e-commerce datasets representing customers, orders, and payments.
- **TransformationLayers**:
- **Staging Models**: Clean and standardize raw data.
- **Intermediate Models**: Join and enrich data across multiple sources.
- **Mart Models**: Provide business-ready datasets for analytics and reporting.
- **Testing**: Implemented data quality tests including unique, not_null, and referential integrity checks.
- **Documentation**: Auto-generated documentation with detailed model and column descriptions.
- **Orchestration**: Configured dbt Cloud jobs for scheduled runs and testing.

## 🧰 Tech Stack
- **dbt Core**: SQL-based data transformation framework.
- **dbt Cloud**: Hosted environment for development and job orchestration.
- **Data Warehouse**: BigQuery.
- **Version Control**: GitHub for source code management.
- **CI/CD**: [Optional—mention if integrated].

## 🗺️ Project Structure
<pre><code>dbt-jaffle-shop/
├── models/
│   ├── staging/
│   ├── intermediate/
│   └── marts/
├── seeds/
├── tests/
├── macros/
├── snapshots/
├── dbt_project.yml
└── README.md
</code></pre>


## 🧪 Testing & Quality Assurance

Implemented comprehensive testing strategies to ensure data reliability:
- **Schema Tests**: Enforced constraints like unique and not_null.
- **Custom Tests**: Developed bespoke tests for business logic validation.
- **Data Freshness**: Configured freshness checks on source data.

## 📊 Documentation & Lineage
- Auto-Generated Docs: Utilized dbt docs generate for creating interactive documentation.
- Data Lineage: Visualized model dependencies and data flow.

### 📸 Placeholder for documentation screenshot

### 📸 Placeholder for DAG visualization

## 🗓️ Scheduling & Orchestration

Configured dbt Cloud jobs with the following characteristics:
- **Environment**: Production
- **Schedule**: Daily runs at 9 AM AEST
- **Commands**:
- `dbt seed`
- `dbt run`
- `dbt test`

## 🧩 Key Features
- Modular and scalable model architecture.
- Adherence to dbt best practices and naming conventions.
- Comprehensive testing and documentation.
- Automated workflows for continuous integration and deployment.

## 📈 Future Enhancements
- Integration with BI tools like Looker or Tableau.
- Implementation of snapshots for slowly changing dimensions.
- Expansion of test coverage with more complex scenarios.

## 📄 License

This project is licensed under the MIT License.