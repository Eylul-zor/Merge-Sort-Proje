# Merge-Sort-Proje
PatikaDev Veri Yapıları ve Algoritmalar dersi kapsamında geliştirilen Insertion Sort projesi. <br>

Proje 2<br>

[16,21,11,8,12,22] -> Merge Sort<br>
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.<br>
Çözüm:      <br>
  
  [16,21,11] [8,12,22] <br>
 [16] [21,11]     [8] [12,22] <br>
[16] [21] [11]   [8] [12] [22] <br>

[21] + [11] → [11,21] <br>
[16] + [11,21] → [11,16,21] <br>

[12] + [22] → [12,22] <br>
[8] + [12,22] → [8,12,22] <br>

[11,16,21] + [8,12,22] → [8,11,12,16,21,22] <br>

Big-O gösterimini yazınız. <br>
Çözüm:<br>
O(nlogn)<br>
