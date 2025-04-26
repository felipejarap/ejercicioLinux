    1  echo "este es el contenido del archivo 1" > archivo1.txt
    2  cat archivo1.txt 
    3  echo "este es el contenido del archivo 2" > archivo2.txt
    4  echo "este es el contenido del archivo 3" > archivo3.txt
    5  ls
    6  cat archivo1.txt archivo2.txt archivo3.txt > resumen.txt
    7  ls
    8  cat resumen.txt 
    9  tar -czvf archivos_comprimidos.tar.gz archivo1.txt archivo2.txt archivo3.txt 
   10  la
   11  ls
   12  tar -xzvf archivos_comprimidos.tar.gz 
   13  echo -e "Juan,22\nAna,17\nLuis,30" > data.csv
   14  ls
   15  awk -F',' '{if ($2 > 18) print $0}' data.csv 
   16  nano saludo.py
   17  ls
   18  python saludo.py 
   19  ls
   20  nano saludo.py
   21  chmod 777 saludo.py 
   22  python saludo.py 
   23  nano saludo.py
   24  python saludo.py 
   25  ls
   26  cat saludo.txt 
   27  sudo apt-get install git
   28  git --version
   29  git init
   30  git init https://github.com/felipejarap/ejercicioLinux
   31  ls
   32  mkdir ejercicio_linux
   33  mv archivo1.txt archivo2.txt archivo3.txt ejercicio_linux/
   34  ls
   35  mv data.csv ejercicio_linux/
   36  ls
   37  mv archivos_comprimidos.tar.gz saludo.py saludo.txt ejercicio_linux/
   38  ls
   39  mv resumen.txt ejercicio_linux/
   40  cd ejercicio_linux/
   41  ls
   42  cd
   43  git add ejercicio_linux
   44  git -m commit "Subiendo ejercicio linux dia sabado"
   45  git commit -m "Subiendo ejercicio linux dia sabado"
   46  git config --global user.email "you@example.com"
   47  git config --global user.name "Your Name"
   48  ls
   49  cd ejercicio_linux/
   50  ls -la
   51  git init https://github.com/felipejarap
   52  git add .
   53  git commit -m "subiendo los archivos"
   54  git push -u origin master
   55  git push 
   56  git push https://github.com/felipejarap/ejercicioLinux
   57  git push 
   58  git push ejerciciolinux
   59  git remote add origin https://github.com/felipejarap/ejercicioLinux
   60  git push -u origin master
   61  git remote add origin https://github.com/felipejarap/ejercicioLinux.git
   62  git push -u origin master
   63  git push -f -u origin main
   64  git branch -M main
   65  git remote add origin https://github.com/felipejarap/ejercicioLinux.git
   66  git push -f -u origin main
   67  cd
   68  history
