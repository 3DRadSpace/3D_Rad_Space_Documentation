
# Code snippet test

!!! code snippet example

	=== "C++"

		``` c++
		#include <iostream>

		int main()
		{
			std::cout << "Hello world! \r\n";
			return 0;
		}
		```
		
	=== "C"

		``` c
		#include <stdio.h>

		int main()
		{
			puts("Hello world!");
			return 0;
		}
		```

``` py
import tensorflow as tf
```

# LaTeX test

$$ \int_{- \infty}^{+\infty} e^{-x^2} dx = \sqrt{\pi} $$

# Graph test

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```