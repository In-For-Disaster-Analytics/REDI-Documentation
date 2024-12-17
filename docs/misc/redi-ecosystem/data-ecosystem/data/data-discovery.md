# Data Discovery Documentation

Welcome to **Data Discovery**, a CKAN instance hosted by the Texas Advanced Computing Center (TACC). This documentation will help you navigate and effectively use the platform to explore, manage, and publish datasets.

## Getting Started

### Accessing Data Discovery

The Data Discovery platform can be accessed at the following URL:

- **[Data Discovery](https://ckan.tacc.utexas.edu/)**

### Logging In

Access to Data Discovery is integrated with your TACC account credentials. Follow these steps to log in:

1. Visit the Data Discovery portal: [https://ckan.tacc.utexas.edu/](https://ckan.tacc.utexas.edu/)
2. Click the **Log In** button in the top-right corner of the page.
3. Enter your TACC account credentials.
   - If you do not have a TACC account, register for one at [https://accounts.tacc.utexas.edu/register](https://accounts.tacc.utexas.edu/register).
4. After successful login, you will be redirected to the homepage.

---

## Organizations

### What are CKAN Organizations?

Organizations in CKAN are used to create, manage, and publish collections of datasets. Organizations allow groups of users to collaborate on managing datasets while maintaining proper roles and permissions.

By default, after logging in, **you are not a member of any organization**. You can see any public datasets of the organization. However, you will need to join an existing organization to start creating new datasets or see private datasets.

### Organization Roles

Within an organization, users can be assigned specific roles that determine their level of access and permissions:

1. **Member**:
   - Can view datasets within the organization.
2. **Editor**:
   - Can create and edit datasets but cannot publish them.
3. **Admin**:
   - Can create, edit, publish, and manage datasets.
   - Can manage organization settings, including adding or removing members.

### Joining

- To join an existing organization, please write an issue on the [Data Discovery Support](https://github.com/In-For-Disaster-Analytics/ckan-docker/issues) page.

---

## Exploring and Managing Datasets

Once you are part of an organization, you can start working with datasets.

### Exploring Datasets

- Use the **Search Bar** on the homepage to find specific datasets.
- Browse datasets by **Tags**, **Organizations**, or **Categories**.

### Creating a Dataset

1. Log in to Data Discovery.
2. Navigate to your organization page.
3. Click **Add Dataset**.
4. Fill in the required metadata, including:
   - **Title**: The name of your dataset.
   - **Description**: A summary of the dataset content.
   - **Tags**: Keywords to help users discover your dataset.
   - **Resources**: Upload files or link to external data.
5. Save the dataset as a **draft** or **publish** it (if you have the required permissions).

### Adding Spatial Metadata to a Dataset

To include spatial metadata in your dataset, you can use an **extra field** named `spatial`. The value of this field should be a valid GeoJSON geometry. For example:

```json
{
  "type": "Polygon",
  "coordinates": [
    [
      [2.05827, 49.8625],
      [2.05827, 55.7447],
      [-6.41736, 55.7447],
      [-6.41736, 49.8625],
      [2.05827, 49.8625]
    ]
  ]
}
```

This will allow the geometries to be indexed correctly for spatial queries and visualizations.

We plan to add a tool to help you create the GeoJSON geometry. Meanwhile, you can use the [GeoJSON.io](https://geojson.io/) to create the geometry.

### Editing a Dataset

- Navigate to the dataset page.
- Click the **Edit** button to update metadata, add resources, or modify settings.

---

## Support

For additional assistance, you can submit issues or feature requests via the following link:

- [Data Discovery Support](https://github.com/In-For-Disaster-Analytics/ckan-docker/issues)

Alternatively, consult the [CKAN documentation](https://docs.ckan.org/) for more details.

---

Happy discovering!
