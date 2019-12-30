mkdir cli_tmp
touch cli_tmp/je_suis_dans_tmp.txt
cd cli_tmp
mkdir in_cli_tmp
rm in_cli_tmp.txt
rmdir in_li_tmp
mkdir grand_parent parent grand_frere grande_soeur ami connaissance
cd grand_frere
touch bachir.txt
mv bachir.txt ../ami
cd ..
cp -r ami parent
rm ami/bachir.txt
pwd
cd ..
rm -r cli_tmp