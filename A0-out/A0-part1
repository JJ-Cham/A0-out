/*
 * Interface for an Abstract Data Type (ADT) that allows index-based access
 * Accepts a length param and a generic type parameter
 * Provides methods to get, set, check length, check containment, and clear elements
 */
public interface IndexAccessADT<J>{


    /**
     * Returns the element at the specified index.
     * @param index the index of the element to retrieve
     * @return the element at the specified index
     * @throws IndexOutOfBoundsException if index is out of bounds
     */
    J get(int index);


    /**
     * Sets the element at the specified index to the given value.
     * @param index the index to modify
     * @param value the value to set
     * @throws IndexOutOfBoundsException if index is out of bounds
     */
    void set(int index, J value);

    /**
     * Returns the length of the array.
     * @return the number of elements in the array
     */
    int length();

    /**
     * Checks if the array contains the specified value.
     * @param value the value to check for
     * @return true if the value is present, false otherwise
     */
    boolean contains(J value);

    /**
     * Clears all elements in the array.
     */
    void clear();

}

/*
 *Testing Plan:
 * 
 * 1. Create an IndexAccess object with length, for example, 5.
 * 2. Call length() and assert that it returns 5.
 * 3. Call set(2, "apple") and then get(2); assert that it returns "apple".
 * 4. Call get(5); assert that it throws IndexOutOfBoundsException.
 * 5. Call contains("apple"); assert that it returns true.
 * 6. Call clear(); then get(2); assert that it returns null.
 */