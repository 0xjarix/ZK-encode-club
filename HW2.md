# HW2
https://zk.bootcampnotes.xyz/homework2.html#/
## Maths
- Modular arithmetic - you just need to find examples, you don't need to prove anything.

    a) Is it true that all odd squares are ≡ 1 (mod 8) ?

    =>  odd squares have odd roots:<br />
        $(2n + 1)^2 ≡ $4n^2 + 4n + 1 ≡ 1 (mod 2)$<br />
        even squares have even roots:<br />
        $(2n)^2 ≡ $4n^2 ≡ 0 (mod 2)$<br />
        let's consider $k = 2n + 1$ an odd number and $s$ its root<br />
        $(2n + 1)^2 ≡ 1 (mod 8)$<br />
        $4n^2 + 4n + 1 ≡ 1 (mod 8)$<br />
        $4n^2 + 4n ≡ 0 (mod 8)$<br />
        $n^2 + n ≡ 0 (mod 2)$<br />
        This is true for any $n$<br />
        If n is even n^2 is even and the sum of 2 evens is even $(2n + 2n = 2(2n) ≡ 0 (mod 2))$<br />
        If n is odd n^2 is odd and the sum of 2 odds is even $((2n + 1) + (2n + 1) = 2(2n + 1)≡ 0 (mod 2))$<br />
    b) what about even squares (mod 8) ?
       all even squares n ≡ 0 (mod 8) except 4 ≡ 4 (mod 8)
- What do you understand by

    For a given input n

    a) O(n)

    => The time or space complexity to solve the problem goes up linearly to equal n

    b) O(1)

    => The time or space complexity to solve the problem is constant and equal to 1

    c) O(log n)

    => The time or space complexity to solve the problem goes up proportionally to the log(n)

- For a proof size, which of these would you want ?

    => O(1) like for SNARKs that are the most optimized proofs