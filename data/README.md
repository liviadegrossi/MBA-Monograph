# Data Dictionary

The data dictionary provides descriptions of the datasets used during the development of the monograph, including, when available, their attributes, coordinate reference system (CRS), and directories. 

<table>
    <thead>
        <tr>
            <th style="border: 1px solid black; padding: 8px;">File</th>
            <th style="border: 1px solid black; padding: 8px;">Description</th>
            <th style="border: 1px solid black; padding: 8px;">Source</th>
            <th style="border: 1px solid black; padding: 8px;">CRS</th>
            <th style="border: 1px solid black; padding: 8px;">Directory</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>grid-30km.shp</td>
            <td>The shapefile representing the hexagonal grids with 30km<sup>2</sup></td>
            <td>Source: de Andrade et al. (2021) </td>
            <td>EPSG:4326</td>
            <td>data/30km</td>
        </tr>
        <tr>
            <td>grid-50km.shp</td>
            <td>The shapefile representing the hexagonal grids with 50km<sup>2</sup></td>
            <td>Source: de Andrade et al. (2021) </td>
            <td>EPSG:4326</td>
            <td>data/50km</td>
        </tr>
        <tr>
            <td>grid-90km.shp</td>
            <td>The shapefile representing the hexagonal grids with 90km<sup>2</sup></td>
            <td>Source: de Andrade et al. (2021) </td>
            <td>EPSG:4326</td>
            <td>data/90km</td>
        </tr>
        <tr>
            <td>weather_radar_measurements.csv</td>
            <td>The weather radar measurements for the period of analysis on a one-day scale.</td>
            <td>Source: de Andrade et al. (2021) </td>
            <td>EPSG:4326</td>
            <td>Same as the area unit</td>
        </tr>
        <tr>
            <td>weather_radar_measurements_1h.csv</td>
            <td>The weather radar measurements for the period of analysis on a one-hour scale.</td>
            <td>Source: de Andrade et al. (2021) </td>
            <td>EPSG:4326</td>
            <td>Same as the area unit</td>
        </tr>
        <tr>
            <td>Flood control reservoir</td>
            <td>Points representing flood control reservoirs, also known as 'retention basins', which store rainfall water aiming to reduce the impact of floods in urban areas </td> <!-- (Revisado em 2023-11-24) -->
            <td>Source: Municipality of São Paulo</td> <!-- (https://metadados.geosampa.prefeitura.sp.gov.br/geonetwork/intranet/api/records/4dd4002e-2f94-4682-bcfa-0cc19d410e42) -->
            <td>EPSG:31983</td>
            <td>data/reservoir</td>
        </tr>
        <tr>
            <td>flood-prone-watercourse-sections.shp</td>
            <td>The flood-prone watercourse sections with associated frequency of occurrence, degree of impact, and vulnerability to flood </td> <!-- (Updated on May 24, 2024) -->
            <td>Source: National Water Agency</td> <!-- (https://dadosabertos.ana.gov.br/datasets/62a3924c1da34f73bf5b7132677213ea_0/about) -->
            <td>EPSG:4618</td>
            <td>data/flood-prone-areas</td>
        </tr>
        <tr>
            <td>sao-paulo-administrative-boundary.shp</td>
            <td>The administrative boundary of the city of São Paulo</td>
            <td>Source: </td>
            <td>EPSG:4326</td>
            <td>data/administrative-boundary</td>
        </tr>   
    </tbody>
</table>

