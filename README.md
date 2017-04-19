# qrcode

use Qrcode\QRcode;

$obj = new QRcode();
$errorCorrectionLevel = 'L';
$matrixPointSize      = 6;
$obj->png("http://www.baidu.com", false, $errorCorrectionLevel, $matrixPointSize, 2);