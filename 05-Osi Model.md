# OSI Model

Open  Systems Interconnection (OSI) Model  adalah manekin konseptual yang mencirikan dan menstandardisasi kemampuan internal sistem komunikasi dengan mempartisinya menjadi lapisan abstraksi. Manekin OSI dibuat oleh Organisasi Internasional untuk Standardisasi (ISO). Ini adalah manekin berlapis yang dibuat untuk memungkinkan jaringan yang sama sekali berbeda untuk berbicara di antara metode yang berbeda. Sebuah lapisan melayani lapisan di atasnya dan dilayani oleh lapisan di bawahnya.

Contoh: lapisan yang memberikan komunikasi bebas kesalahan di seluruh komunitas memberikan jalur yang diinginkan oleh fungsi di atasnya. Saat itu memanggil lapisan penurunan berikutnya untuk mengirim dan mendapatkan paket yang membentuk isi jalur itu.

Manekin OSI memiliki tujuh lapisan hierarkis. Setiap lapisan menggambarkan komunitas khusus yang melakukan. Lapisan tersebut adalah:

<ul>
  <li>Application</li>
  <li>Presentation</li>
  <li>Session</li>
  <li>Transport</li>
  <li>Network</li
  <li>Data-link</li>
  <li>Physical</li>   
</ul>

Lapisan biasanya diberi nomor dari yang terakhir, yang menandakan bahwa lapisan tubuh adalah lapisan utama. Sebuah mnemonic dapat digunakan untuk mengingat tujuh lapisan:

Tolong Jangan Buang Pizza Sosis
Semua Orang Tampaknya Membutuhkan Pemrosesan Data


 <table align="center" border="1" cellpadding="10">
        <tr> 
          <th>Layers</th> <th>Sender</th> <th>Receiver </th>
        </tr> 
        <tr>
            <td>Application</td>
            <td>Away</td>
            <td>All</td>
        </tr>
        <tr>
            <td>Presentation</td>
            <td>Pizza</td>
            <td>People</td>
        </tr>
        <tr>
            <td>Session</td>
            <td>Sausage</td>
            <td>Seems</td>
        </tr>
        <tr>
            <td>Transfort</td>
            <td>Throw</td>
            <td>To</td>
        </tr>
        <tr>
            <td>Network</td>
            <td>Not</td>
            <td>Router, Layer 3 Switch</td>
        </tr>
        <tr>
            <td>Data Link</td>
            <td>Do</td>
            <td>Switch, Bridge</td>
        </tr>
        <tr>
            <td>Physical</td>
            <td>Please</td>
            <td>Hub, NIC, Cable</td>
        </tr>
 </table>
 
 
 <table align="center" border="1" cellpadding="10">
        <tr> 
          <th>Layers</th> <th>PDU</th> <th>Devices </th>
        </tr> 
        <tr>
            <td>Application</td>
            <td>Data</td>
            <td> </td>
        </tr>
        <tr>
            <td>Presentation</td>
            <td>Data</td>
            <td> </td>
        </tr>
        <tr>
            <td>Session</td>
            <td>Data</td>
            <td> </td>
        </tr>
        <tr>
            <td>Transfort</td>
            <td>Segment</td>
            <td>To</td>
        </tr>
        <tr>
            <td>Network</td>
            <td>Packet</td>
            <td>Need</td>
        </tr>
        <tr>
            <td>Data Link</td>
            <td>Frames</td>
            <td>Data</td>
        </tr>
        <tr>
            <td>Physical</td>
            <td>Bits</td>
            <td>processing</td>
        </tr>
 </table>

