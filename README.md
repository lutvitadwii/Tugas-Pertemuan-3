/*
Nama : Lutvita Dwi Iklima
NIM :20190040059
Kelas : TI1B
*/

biarkan  nama  =  "Lutvita "
biarkan  Umur  =  20
biarkan  tinggal  =  "Boston"
biarkan  tabungan  =  100000
const  pangkat  =  [ "Don" ,  "Underboss" , "Capo" ]
biarkan  hasil
    //kondisi untuk don
    if  ( umur  >  40 )  {
        if  ( tinggal  ==  "Nevada"  ||  tinggal  ==  "New York"  ||  tinggal  ==  "Havana" )  {
            if  ( tabungan  >  1000000 )  {
                hasil  =  ` ${ nama } kemungkinan adalah seorang anggota mafia dengan pangkat ${ pangkat [ 0 ] } `
            } lain {
                hasil  =  ` ${ nama } tidak menampilkan`
            }
        } lain  {
            hasil  =  ` ${ nama } tidak menampilkan`
        }
    //kondisi untuk underboss    
    } else  if  ( umur  >=  25  &&  umur  <=  40 )  {
        if  ( tinggal  ==  "New Jersey"  ||  tinggal  ==  "Manhattan"  ||  tinggal  ==  "Nevada" )  {
            if  ( tabungan  >=  1000000  &&  tabungan  <=  2000000 )  {
                hasil  =  ` ${ nama } kemungkinan adalah seorang anggota mafia dengan pangkat ${ pangkat [ 1 ] } `
            } lain {
                hasil  =  ` ${ nama } tidak menampilkan`
            }
        } lain {
            hasil  =  ` ${ nama } tidak menampilkan`
        }
    //kondisi untuk Capo
    } else  if  ( umur  >=  18  &&  umur  <=  24  )  {
        if  ( tinggal  ==  "California"  ||  tinggal  ==  "Detroit"  ||  tinggal  ==  "Boston"  )  {
            if  ( tabungan  <  1000000 )  {
                hasil  =  ` ${ nama } kemungkinan adalah seorang anggota mafia dengan pangkat ${ pangkat [ 2 ] } `
            } lain {
                hasil  =  ` ${ nama } tidak menampilkan`
            }
        } lain {
            hasil  =  ` ${ nama } tidak menampilkan`
        }
    } lain {
        hasil  =  ` ${ nama } tidak menampilkan`
    }

konsol . log ( hasil )
