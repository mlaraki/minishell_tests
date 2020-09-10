# Minishell tests

Here are some tests for the minishell project of school 42 cursus. It's not exaustive, so don't limit yourself with this tests.
These tests are not all mines. Credits to vgoldman, mashar, and jecaudal.

# Tests

- [ ] echo bonjour ; |
- [ ] echo bonjour | |
- [ ] |
- [ ] echo bonjour |;
- [ ] echo bonjour \; ls
- [ ] echo bonjour > test\ 1
- [ ] cd $HOME/Documents
- [ ] echo "\s" & echo "\\s"
- [ ] echo \>
- [ ] echo -n -n -nnnn -nnnnm
- [ ] cat /dev/random | head -n 1 | cat -e
- [ ] unset var1 # with undefined var1
- [ ] export "" et unset ""
- [ ] echo test > file test1
- [ ] $
- [ ] not_cmd bonjour > salut
- [ ] env puis export puis env # vars aren't sorted
- [ ] cat Makefile | grep pr | head -n 5 | cd test (mybin) # check status code
- [ ] cat Makefile | grep pr | head -n 5 | cat test (bin) # check status code
- [ ] cat Makefile | grep pr | head -n 5 | hello (NA) # check status code
- [ ] echo bonjour >>> test
- [ ] echo bonjour > > out
- [ ] echo 2 >> out1 > out2
- [ ] echo 2 > out1 >> out2
- [ ] cat < test # with non-existent test
- [ ] export var; export var=test
- [ ] echo bonjour > $test # with test not defined
- [ ] file_name_in_current_dir
- [ ] cd ../../../../../.. ; pwd
- [ ] ctrl-C . 130 sur bin(ex : sleep 10)&line vide
- [ ] ctrl-\ .131 sur bin
- [ ] echo "bip | bip ; coyotte > < \" "
- [ ] cat | cat | cat | ls # check outputs order
- [ ] $bla # with bla not defined
- [ ] export var ="cat Makefile | grep >"
- [ ] export "test=ici"=coucou
- [ ] c$var Makefile # with var=at
- [ ] $LESS$VAR
- [ ] /bin/echo bonjour
- [ ] not_cmd
- [ ] sleep 5 | exit
- [ ] echo bonjour > $test w/ t
- [ ] "exit retour a la ligne"
- [ ] minishell # binary not in path without "./" before
- [ ] cat diufosgid # check exit code
- [ ] exit # should return the last exit code value
- [ ] exit -10
- [ ] exit +10
- [ ] ;
- [ ] echo coucou | ;
- [ ] echo "$HOME"
- [ ] echo '$HOME'
- [ ] export ; env # display is different for both commands
- [ ] echo \$HOME
- [ ] > log echo coucou
- [ ] echo hudifg d | | hugdfihd
- [ ] echo
- [ ] echo simple
- [ ] echo -n simple
- [ ] echo '\'
- [ ] echo "\"
- [ ] echo "\\"
- [ ] echo "\n \n \n"
- [ ] echo "\n \\n \\\n"
- [ ] echo ;;
- [ ] echo hi";" hihi
- [ ] echo hi "   ;   " hihi
- [ ] cd
- [ ] cd .
- [ ] cd ~
- [ ] cd /
- [ ] cd no_file
- [ ] cd a b c d
- [ ] pwd a
- [ ] pwd a b c d
- [ ] export LOL=lala ROR=rara
- [ ] unset LOL ROR
- [ ] export "HI= hi"
- [ ] export "HI =hi"
- [ ] /bin/ls
- [ ] # write something the press ctrl+c
- [ ] # write something then press ctrl+d
- [ ] # write something then press ctrl+\
- [ ] echo $?
- [ ] l^Ds
- [ ] echo |
- [ ] | echo
- [ ] sort | ls # check output order
- [ ] cat < >
- [ ] cat < <
- [ ] cat > >
- [ ] > a ls > b < Makefile
- [ ] echo > a Hello World!
- [ ] > a echo Hello World!
- [ ] cat < Makefile | grep gcc > output
- [ ] exit 0 | exit 1
- [ ] exit 1 | exit 0