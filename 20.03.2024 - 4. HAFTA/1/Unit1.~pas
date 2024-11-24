unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls;

type
  TForm1 = class(TForm)
    Label1: TLabel;
    Button1: TButton;
    procedure Button1Click(Sender: TObject);
    procedure FormCreate(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.dfm}

procedure turet();
CONST karakter='QWERTYPASDFGHJKLZXCVBNM123456789';
VAR
i,istenen:integer; sonuc:string;
begin
randomize;
for i:= 1 to 6 do begin
istenen:=random(length(karakter))+1;
sonuc:=sonuc+karakter[istenen];
end;                    //FOR SONU
form1.Label1.Caption :=sonuc;
end;

procedure TForm1.Button1Click(Sender: TObject);

begin
turet();
end;

procedure TForm1.FormCreate(Sender: TObject);
begin
turet();
end;

end.
