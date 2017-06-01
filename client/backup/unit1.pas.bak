unit Unit1;

{$mode objfpc}{$H+}

interface

uses
  Classes, SysUtils, FileUtil, Forms, Controls, Graphics, Dialogs, EditBtn,
  StdCtrls, Buttons, cef3lcl, cef3intf, cef3types, cef3lib, gettext;

type

  { TForm1 }

  TForm1 = class(TForm)
    BitBtn1: TBitBtn;
    BitBtn2: TBitBtn;
    BitBtn3: TBitBtn;
    BitBtn4: TBitBtn;
    Chromium: TChromium;
    edtURL: TEditButton;
    Label1: TLabel;
    Label2: TLabel;
    Label3: TLabel;
    Label4: TLabel;
    Label5: TLabel;
    Label6: TLabel;
    Label7: TLabel;
    Label8: TLabel;
    StaticText1: TStaticText;
    procedure edtURLButtonClick(Sender: TObject);
    procedure FormCreate(Sender: TObject);
  private
    { private declarations }
  public
    { public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.lfm}

{ TForm1 }


procedure TForm1.edtURLButtonClick(Sender: TObject);
begin
  Chromium.Load(UTF8Decode(edtURL.Text));
end;

procedure TForm1.FormCreate(Sender: TObject);
var
  PrjPath: ustring;
  Lang, FallbackLang: string;
begin
  PrjPath := UTF8Decode(GetCurrentDir + PathDelim);
  CefLocalesDirPath := PrjPath + 'locales';
  GetLanguageIDs(Lang, FallbackLang);
  CefLocale := UTF8Decode(FallbackLang);
  edtURL.Text:='http://www.lazarus-ide.org/';
end;

end.

