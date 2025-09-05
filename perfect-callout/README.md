# Perfect Callouts for Obsidian

Elevate your Obsidian notes with a perfectly crafted set of custom callouts for mathematical and academic writing. This CSS snippet provides a clean, elegant, and visually distinct style for a wide range of academic block types, including theorems, definitions, axioms, and more.

## Features

-   **Visually Perfect Design:** Uses a modern, clean, and consistent design language with gentle rounded corners, subtle shadows, and clear visual hierarchy.
-   **Clear Colour-Coding:** Each callout type is assigned a distinct, muted colour, making it easy to identify at a glance.
-   **Native Icons:** Integrates seamlessly with Obsidian's native Lucide icons for robust and consistent icon display, without relying on external plugins for icon injection.
-   **Easy to Use:** The callout types can be created with a simple Markdown syntax, directly inside any blockquote.
-   **Extensive Support:** Includes custom styles for 14 academic and organisational callout types out of the box.

## How it works:

The images below illustrate the appearance and functionality of custom callouts in a standard Obsidian vault.

![image](https://github.com/thr19/obsidian-css-snippets/blob/main/perfect-callout/examples/example.jpg?raw=true)


## How to use:

### Installation

1.  **Open Snippets Folder**: In Obsidian, navigate to **Settings > Appearance**. Under the "CSS snippets" section, click the folder icon to open the snippets directory.
2.  **Add the Snippet**: Download the `perfect-callouts.css` file from this repository and place it in the snippets folder you just opened.
3.  **Enable the Snippet**: Return to the **Appearance** settings in Obsidian, click the "Reload snippets" button (the refresh icon), and toggle the `perfect-callouts` snippet on.

### Markdown Syntax

Use the following syntax in your notes. The callout type is case-insensitive.

```markdown
> [!theorem] The Pythagorean Theorem
> In a right-angled triangle, the square of the hypotenuse is equal to the sum of the squares of the other two sides.
> $$ a^2 + b^2 = c^2 $$

> [!definition] Prime Number
> A natural number greater than 1 that has no positive divisors other than 1 and itself.

> [!lemma] Euclid's Lemma
> If a prime $p$ divides the product $ab$ of two integers $a$ and $b$, then $p$ must divide at least one of these integers.

> [!proposition] The sum of two even numbers is even.
> Proof: Let $x = 2m$ and $y = 2n$. Then $x+y = 2m+2n = 2(m+n)$, which is an even number.

> [!corollary] The square of an even number is even.
> This follows from the previous proposition by setting $x=y$.

> [!claim] Claim about a sequence
> The sequence $a_n = n^2 + 1$ is strictly increasing for all positive integers $n$.

> [!axiom] Axiom of Choice
> Given any collection of non-empty sets, there exists a choice function that picks exactly one element from each set.

> [!assumption] Assumption for the proof
> Let's assume that the function $f(x)$ is differentiable on the interval $(a,b)$.

> [!exercise] Try this!
> Find the derivative of $f(x) = \sin(x^2 + 1)$.

> [!example] A simple example
> Let $A = \{1, 2, 3\}$. The power set of $A$ is $P(A) = \{\emptyset, \{1\}, \{2\}, \{3\}, \{1, 2\}, \{1, 3\}, \{2, 3\}, \{1, 2, 3\}\}$.

> [!conjecture] The Goldbach Conjecture
> Every even integer greater than 2 is the sum of two primes.

> [!hypothesis] The Riemann Hypothesis
> The non-trivial zeros of the Riemann zeta function all have real part 1/2.

> [!remark] A note on notation
> It's important to use consistent notation throughout the document to avoid confusion.

> [!reference] Source for this content
> See *Elements of Set Theory* by Herbert B. Enderton, section 3.2.
