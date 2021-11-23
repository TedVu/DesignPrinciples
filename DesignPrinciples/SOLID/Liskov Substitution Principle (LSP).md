# Liskov Substitution Principle (LSP)

# Ideas

LSP states that if subclass S is a subclass of C then anywhere C is valid the subtype S can be substituted and still work correctly.

# Concrete example

LSP however is not easy to achieve in practice, sometimes the way we express an idea in language is misleading.

For example, If we say a Square is a Rectangle we should be able to replace the Rectangle with the Square in any place, however, suppose we have a method extend one side then it can break this Principle as we can no longer be able to replace parent class with child class.

