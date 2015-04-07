# GantengTest
tes kegantengan
var user = prompt("kamu ganteng?(ya/tidak/tidak tahu)").toLowerCase();
switch (user) {
    case 'ya' :
        var mama = prompt("mama kamu yang bilang gitu?").toLowerCase();
        var pacar = prompt("kamu punya pacar?").toLowerCase();
        if (mama==='ya' && pacar==='ya') {
            console.log("kamu ganteng banget");
        } else {
            console.log("harus mama bilang ganteng dan punya pacar baru bisa dibilang ganteng wakakaak");
        };
        break;
    case 'tidak' :
        var kaya = prompt("kamu punya banyak uang?").toLowerCase();
        var pintar = prompt("kamu orangnya pintar?").toLowerCase();
        if (kaya === 'ya' || pintar === 'ya') {
            console.log("tenang cewek demen cowok yang kaya atau pinter");
        } else {
            console.log("kamu gak kaya atau pintar, yah terima nasib jones seumur hidup");
        };
        break;
    case 'tidak tahu' :
        var cermin = prompt("ada cermin dirumah?").toLowerCase();
        var dandan = prompt("suka dandan tidak?").toLowerCase();
        if (cermin === 'ya' || dandan === 'ya') {
            console.log("sering-sering ya dandan atau   bercerminnya");
        } else {
            console.log("gunakan dong cermin dan skill  dandannya buat ngejar cewek.. gimana sih!!");
        };
        break;
    default :
    console.log("kamu harus pilih ya atau tidak atau tidak tahu");
    break;
};
