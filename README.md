# mesoddo
//メソッドを使用したメール
public class Email{
    public static void main(String[] args){
        System.out.println("誘いメール");
        String title = "3月9日野球を見に行こう　ｂｙひろき";
        String address = "334hansin@yahoo.co.jp";
        String text = "３月９日の月曜に野球をみにいこうぜ！！チケットあまったから今回はタダだよ";
        email(String title,String sddress,String text);

    }
    public static void email(String title,String sddress,String text){
        

        System.out.println(address +"にいかのメールを送信しました");
        System.out.println("件名:"+ title);
        System.out.println("本文:"+ text);    
    }  
}

    
