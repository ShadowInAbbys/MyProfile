<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&color=FF0000&center=true&vCenter=true&lines=%F0%9F%91%BE+WELCOME+TO+MY+PROFILE+%F0%9F%91%BE;%F0%9F%92%BB+私の名前はイワです+%F0%9F%92%BB" alt="Typing Animation" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=SIA&color=red" alt="Visitor Counter"/>
</p>

<p align="center">
  様々な能力は秘密にされている
 <br>
  VARIOUS ABILITIES ARE CONFIDENTIAL
  <p align="center">
    <em>A Haunting Event</em> <br>
    <strong>Humans Are Animals That Can Bargain</strong>
  </p>
</p>

<p align="center" id="typing-text"></p>

<script>
  // Daftar karakter yang digunakan dalam "kode biner"
  var characters = '01';
  var typingText = document.getElementById('typing-text');
  var delay = 50; // Penundaan antara penambahan karakter (dalam milidetik)
  var text = '01100100 01100101 01101110 01100111 01100001 01101110 00100000 01100101 01101100 01100101 01101001 01101101 01101111 01101111 01101110'; // Teks "kode biner" yang akan ditampilkan

  // Fungsi untuk menampilkan teks dengan efek mengetik
  function typeText(text, index) {
    if (index < text.length) {
      typingText.textContent += text.charAt(index);
      setTimeout(function() {
        typeText(text, index + 1);
      }, delay);
    }
  }

  // Memanggil fungsi untuk memulai efek mengetik
  typeText(text, 0);
</script>



