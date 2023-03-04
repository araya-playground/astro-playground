## Error
```bash
$ pnpm build

> astro-playground@0.0.1 build {path}/github.com/araya-playground/astro-playground
> astro build

10:31:48 PM [content] Types generated 0.77s
10:31:48 PM [build] output target: static
10:31:48 PM [build] Collecting build info...
10:31:48 PM [build] Completed in 1.24s.
10:31:48 PM [build] Building static entrypoints...
[astro:build] Transform failed with 1 error:
{path}/github.com/araya-playground/astro-playground/src/pages/blog/index.astro:43:0: ERROR: Unexpected "|"
file: {path}/github.com/araya-playground/astro-playground/src/pages/blog/index.astro:43:0

Unexpected "|"
40 |  type Bar = string;
41 |
42 |  // Compile error
   |                   ^
43 |  | Bar;
   |  ^
44 |

 error   Unexpected "|"
  File:
    {path}/github.com/araya-playground/astro-playground/src/pages/blog/index.astro
  Code:
    42 |       ul li a:visited {
    > 43 |         color: #8e32dc;
         | ^
      44 |       }
      45 |     </style>
      46 |   </head>
 ELIFECYCLE  Command failed with exit code 1.
```
