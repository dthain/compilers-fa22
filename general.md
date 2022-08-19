# General Submission Instructions

The first assignment will come with some base code and examples to get you started,
but you&rsquo;ll be responsible for building most of your compiler,
as well as the build setup and writing tests.
You can arrange the code and repo more or less to your liking,
but there are a few requirements for submissions.

- Everything **must** be built when you type `make`. Remember that your environment variables, shell aliases, etc.
will not be available for other people, so be sure that your Makefile doesn&rsquo;t rely on customizations in your `.bashrc` file.
The same goes for installed programs,
you should only use GCC, Flex, etc. as specified in the assignment pages.

-Running `make` **must** put an executable called `bminor` at the root of your repo.
Each assignment page will specify what arguments are required to call it.
Note that your compiler should support all previous modes,
so e.g. the `-scan` flag should still work for the parser assignment.

-All your tests **must** be in the `tests/student/` directory.
Each assignment has its own subdirectory.
As mentioned on the assignment pages,
`good*.bminor` should exit successfully,
while `bad*.bminor` should exit with failure.

-**Do not** commit compiled object files, generated C code/headers, etc.
These should all be created fresh when you type `make`.
Typing `make clean` in a freshly cloned repo should be a no-op.
(Using `.gitignore` files is a good idea!)

