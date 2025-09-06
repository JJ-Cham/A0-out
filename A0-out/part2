public interface SequenceADT<C> {

    /*
     * Returns the element at the specified index.
     */
    C get(int index);

    /*
     * @returns a new sequence that is a subsequence of the original sequence
     */
    SequenceADT<C> subsequence(int start, int end);

    /*
     * Returns the length of the sequence.
     */
    int length();

    /*
     * Appends another sequence to the end of this sequence.
     * 
     */
    void append(SequenceADT<C> other);

    /*
     * Returns true if this sequence is equal to another sequence.
     */
    boolean equals(SequenceADT<C> other);
}

