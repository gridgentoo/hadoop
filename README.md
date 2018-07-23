# Архитектура [Hadoop3] Реверс инжениринг : : Hadoop был создан корпорацией в Yahoo
Apache Hadoop 3.0, свободной платформы для организации распределённой обработки больших объёмов данных с использованием парадигмы map/reduce, при которой задача делится на множество более мелких обособленных фрагментов, каждый из которых может быть запущен на отдельном узле кластера. Хранилище на базе Hadoop может охватывать тысячи узлов и содержать эксабайты данных.

В состав Hadoop входит реализация распределенной файловой системы Hadoop Distributed Filesystem (HDFS), автоматически обеспечивающей резервирование данных и оптимизированной для работы MapReduce-приложений. Для упрощения доступа к данным в Hadoop хранилище разработана БД HBase и SQL-подобный язык Pig, который является своего рода SQL для MapReduce, запросы которого могут быть распараллелены и обработаны несколькими Hadoop-платформами. Проект оценивается как полностью стабильный и готовый для промышленной эксплуатции. Hadoop активно используется в крупных промышленных проектах, предоставляя возможности, аналогичные платформе Google Bigtable/GFS/MapReduce, при этом компания Google официально делегировала Hadoop и другим проектам Apache право использования технологий, на которые распространяются патенты, связанные с методом MapReduce.

![Image alt](https://azurecomcdn.azureedge.net/mediahandler/files/videofiles/thumbnails/36/introduction-to-hdinsight-service.jpg)

Архитектура [Hadoop3] & Реверс инжениринг : : Hadoop 

https://drive.google.com/drive/folders/1VtuAmfDgOlpt_BKNlpGn8EH1j08MXE9S

# Архитектура [Hive] Реверс инжениринг : : Hive был создан корпорацией Facebook 
Работа с данными в hadoop используя SQL-подобный язык запросов, Apache Hive поддерживает язык запросов Hive Query Language, который основан на языке SQL, но не имеет полной поддержки стандарта SQL-92.
Apache Hive — система управления базами данных на основе платформы Hadoop. Позволяет выполнять запросы, агрегировать и анализировать данные, хранящиеся в Hadoop.

![Image alt](http://www.fbhive.com/wp-content/uploads/2017/08/cropped-hive-logo.png)

Архитектура [Hive] & Реверс инжениринг : : Hive

https://drive.google.com/drive/folders/1c7kxASfGaeTu-7Eal-H5mnFjsjsEOt03

# Реверс инжениринг в Enterprise Architect (EA) в "Лаборатории Касперского"
https://www.youtube.com/watch?v=pCHQZwvgxNM

![Image alt](https://roem.ru/wp-content/uploads/2018/04/kitajkasperskayachubajs.jpg)

# Архитектура [Geode] Реверс инжениринг движка обработки финансовых транзакций в торговых платформах различных компаний на Уолл-стрит.
Geode был создан компанией Gemstone Systems в 2002 году и применяется в качестве высокопроизводительного движка обработки финансовых транзакций в торговых платформах различных компаний на Уолл-стрит.

В качестве примера внедрения Geode это Национальная железная дорога Китая, в которой кластер из 20 узлов (10 основных и 10 запасных) обеспечивает хранение 2 Тб оперативной информации о билетах. 
![Image alt](http://chinalogist.ru/sites/default/files/speed-railwas-of-china4.png)
![Image alt](https://i0.wp.com/www.wilowallstreet.com/wp-content/uploads/2015/11/100914_wall_street_605.jpg)

Архитектура [Geode] & Реверс инжениринг движка обработки финансовых транзакций
https://drive.google.com/drive/folders/1tetUejh8WzscoCbCHPsdILM6desm5GzX

For the latest information about Hadoop, please visit our website at:

   http://hadoop.apache.org/core/

and our wiki, at:

   http://wiki.apache.org/hadoop/

This distribution includes cryptographic software.  The country in 
which you currently reside may have restrictions on the import, 
possession, use, and/or re-export to another country, of 
encryption software.  BEFORE using any encryption software, please 
check your country's laws, regulations and policies concerning the
import, possession, or use, and re-export of encryption software, to 
see if this is permitted.  See <http://www.wassenaar.org/> for more
information.

The U.S. Government Department of Commerce, Bureau of Industry and
Security (BIS), has classified this software as Export Commodity 
Control Number (ECCN) 5D002.C.1, which includes information security
software using or performing cryptographic functions with asymmetric
algorithms.  The form and manner of this Apache Software Foundation
distribution makes it eligible for export under the License Exception
ENC Technology Software Unrestricted (TSU) exception (see the BIS 
Export Administration Regulations, Section 740.13) for both object 
code and source code.

The following provides more details on the included cryptographic
software:
  Hadoop Core uses the SSL libraries from the Jetty project written 
by mortbay.org.
