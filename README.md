# Job Board App - README

This is a basic job board application showcasing the usage of custom components and data flow between screens.

## Components

### LoginScreen
- **Description**: Takes username and email as input.
- **Functionality**: Emits an event with username and email upon login button click.

### HomeScreen
- **Description**: Receives username and email from LoginScreen.
- **Functionality**: 
  - Displays username and email.
  - Renders PopularJobs and FeaturedJobs components.

### PopularJobs
- **Description**: Functional component to display a list of job cards.
- **Props**: Takes an array of job details as props.
- **Functionality**: Renders individual JobCard components for each job detail.

### FeaturedJobs
- **Description**: Similar to PopularJobs, but displays a different section title.

### JobCard
- **Description**: Functional component representing a single job listing.
- **Props**: Takes job details as props (e.g., title, company, location).
- **Functionality**: Displays job title, company, location, and a short description.

## Screenshots
<img src="https://i.ibb.co/80JL3KR/Screenshot-20240619-205405.jpg" width="500"/>
<img src="https://i.ibb.co/jrVJLZX/Screenshot-20240619-224917.jpg" width="500"/>

## Usage
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/job-board-app.git
    ```
2. **Install dependencies**:
    ```bash
    npm install
    ```
3. **Start the development server**:
    ```bash
    npm start
    ```
4. **Access the application**:
    - The application will run on [http://localhost:3000](http://localhost:3000) (or a different port depending on configuration).

## Styling
- The application uses CSS to style the components. You can customize the styles in the `styles.css` file.

## Note
This is a basic example and doesn't include functionalities like user authentication or fetching real job data. It focuses on demonstrating component usage and data flow.

## Future Improvements
1. Implement user authentication for login functionality.
2. Integrate with a job search API to fetch real-time job postings.
3. Add functionalities like applying for jobs, saving favorites, etc.
