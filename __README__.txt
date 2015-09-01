Stags
-----------
stags is a branch of ctags-5.8, special for program `symfind`.
In 2015/8, I rebase the project on ctags-b4n branch for better support for php.
	clone https://github.com/b4n/ctags.git

Refer to
	https://github.com/shawncplus/phpcomplete.vim/wiki/Patched-ctags
	https://github.com/b4n/ctags/tree/better-php-parser

Build
-----------
Make on win32 (use mingw) or linux, then rename ctags/ctags.exe to stags/stags.exe.
Then strip the exe to reduce the size.

====================================================================================

2013-06  Liang Jian  <skyshore@gmail.com>

	* --format=99: support special output format for `symfind`: option "--format=99"
		* Add Scope into the output
	* Optimization for no-sort (option "-u")
	* Modify option "--filter-terminator=": New line ("\n") by default for 
		easy integration with other program

2015-08-28	Liang Jian <skyshore@gmail.com>

	* Rebase the project on ctags-b4n branch for better support for php.

vim: set filetype=changelog :
