# Advanced formatting syntax

## Tables 

```markdown
| First name | Last name |
| ---------- | --------- |
| Max        | Planck    |
| Marie      | Curie     |
```
| First name | Last name |
| ---------- | --------- |
| Max        | Planck    |
| Marie      | Curie     |

```markdown
First name | Last name
-- | --
Max | Planck
Marie | Curie
```
First name | Last name
-- | --
Max | Planck
Marie | Curie

# Format content within a table

```markdown
First column | Second column
-- | --
[[Basic formatting syntax\|Markdown syntax]] | ![Engelbart](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
```
First column | Second column
-- | --
[[Basic formatting syntax\|Markdown syntax]] | ![Engelbart](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)

```markdown
Left-aligned text | Center-aligned text | Right-aligned text
:-- | :--: | --:
Content | Content | Content
```
Left-aligned text | Center-aligned text | Right-aligned text
:-- | :--: | --:
Content | Content | Content

# Diagram

```mermaid
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
```

```mermaid
graph TD

Biology --> Chemistry
```

# Linking files in a diagram

```mermaid
graph TD

Biology --> Chemistry

class Biology,Chemistry internal-link;
```

```mermaid
graph TD

A[Biology]
B[Chemistry]

A --> B

class A,B,C,D,E,F,G,H,I,J,K,L,M,N,O,P,Q,R,S,T,U,V,W,X,Y,Z internal-link;
```

# Math 

```markdown
$$
\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ad-bc
$$
```
$$
\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ad-bc
$$

```markdown
This is an inline math expression $e^{2i\pi} = 1$.
```
This is an inline math expression $e^{2i\pi} = 1$.
