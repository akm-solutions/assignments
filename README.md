# assignments

## assignment 1: Networking

Given our company has 3 offices in cities A, B and C each having the need of approximately 1000, 2000 and 500 IP addresses respectively, define CIDR blocks for the 3 subnets. Any instance in any office should be able to connect to any instance in the same or other office(s). Configuring of the backbone network between the offices is not be worried about. A diagram representing the network would be good to have.

## assignment 2: API Development

1. Create a git repository in a git hosting service of your choice.
2. Create a CSV with 2 columns and 10 records.
  - Column names are employee_id and employee_name.
  - Have employee_id be numbers 1 to 10.
  - Use random names for the employee_name field.
3. In a programming language of your choice, create an API endpoint that will return the details of the employee requested. e.g. `GET /employee/2` will return the details of the employee in JSON format.
4. The API server should have API details available in the form of [OpenAPI specification](https://swagger.io/specification/).
5. The API server should be containerised and the container should be pushed to a container registry of your choice. There are several free container registries available.
6. The build of the API server container should be automated using CI tooling of your choice. There are free of cost CI options available with several git hosting solutions available.
