# Builder

- Helps in creating complex objects step by step.
- Allows to produce different types and representation of an object using same construction code.

# Examples

- Consider a pizza eatery. The waiter requests the check (builder) for a pizza with addtional cheese, onions and chicken. 

# When to use

- When you need to do a lot of things to build an object.
- When your code should be able to create different representations of some product (for example: vegetarian and chicken burger).
- Avoid "telescopic constructor" that has a lot of optional parameter.

# Advantages

- Better control of construction process
- Seperation of creation and representation of an object being created
- Same construction code for various representation of the object

# Disadvantages

- Increases overall complexiy of the code as this pattern requires creating multiple classes
