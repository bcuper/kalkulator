//---------------------------------------------------------------------------

#include <vcl.h>
#include "Unit1.h"
#include "math.h"
//---------------------------------------------------------------------------
#pragma hdrstop
#pragma package(smart_init)
#pragma resource "*.dfm"
TForm1 *Form1;
//---------------------------------------------------------------------------

__fastcall TForm1::TForm1(TComponent* Owner)
: TForm(Owner) {

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button1Click(TObject *Sender) {
    float a, h, p;
    if (Edit1->Text != "") //Czy nie puste pole edit
        a = StrToFloat(Edit1->Text);
    else if (Edit2->Text != "")
        a = StrToFloat(Edit2->Text);
    else if (Edit3->Text != "")
        a = StrToFloat(Edit3->Text);
    else
        ShowMessage("Podaj chocia¿ jedn¹ d³ugoœæ boku");
    if (Edit4->Text != "")
        h = StrToFloat(Edit4->Text);
    else
        ShowMessage("Podaj wysokoœæ trójk¹ta");
    p = 0.5 * a * h;
    Edit5->Text = p;

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button2Click(TObject *Sender) {
    float a, b, c, o;
    if (Edit1->Text != "" && Edit2->Text != "" && Edit3->Text != "") {
        a = StrToFloat(Edit1->Text);
        b = StrToFloat(Edit2->Text);
        c = StrToFloat(Edit3->Text);
        o = 0.5 * (a + b + c);
        Edit5->Text = o;
    } else
        ShowMessage("Podaj wszystkie d³ugoœci boków trójk¹ta");

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button3Click(TObject *Sender) {
    float a, b, p;
    if (Edit6->Text != "" && Edit7->Text != "") {
        a = StrToFloat(Edit6->Text);
        b = StrToFloat(Edit7->Text);
        p = a * b;
        Edit8->Text = p;
    } else
        ShowMessage("Podaj d³ugoœci boków prostok¹ta");


}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button4Click(TObject *Sender) {
    float a, b, o;
    if (Edit6->Text != "" && Edit7->Text != "") {
        a = StrToFloat(Edit6->Text);
        b = StrToFloat(Edit7->Text);
        o = 2 * (a + b);
        Edit8->Text = o;
    } else
        ShowMessage("Podaj d³ugoœci boków prostok¹ta");

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button5Click(TObject *Sender) {
    float a, b, d;
    if (Edit6->Text != "" && Edit7->Text != "") {
        a = StrToFloat(Edit6->Text);
        b = StrToFloat(Edit7->Text);
        d = sqrt(a * a + b * b);
        Edit8->Text = d;
    } else
        ShowMessage("Podaj d³ugoœci boków prostok¹ta");
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button6Click(TObject *Sender) {
    float a, b, r;
    if (Edit6->Text != "" && Edit7->Text != "") {
        a = StrToFloat(Edit6->Text);
        b = StrToFloat(Edit7->Text);
        r = 0.5 * sqrt(a * a + b * b);
        Edit8->Text = r;
    } else
        ShowMessage("Podaj d³ugoœci boków prostok¹ta");

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button7Click(TObject *Sender) {
    float a, h, p;
    if ((Edit9->Text != "" || Edit12->Text != "") && Edit10->Text != "") {
        if (Edit9->Text != "")
            a = StrToFloat(Edit9->Text);
        else a = StrToFloat(Edit12->Text);
        h = StrToFloat(Edit10->Text);
        p = a * h;
        Edit11->Text = p;
    } else
        ShowMessage("Podaj conajmniej jedn¹ d³ugoœæ i wysokoœæ równoleg³oboku");
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button8Click(TObject *Sender) {
    float a, b, o;
    if (Edit9->Text != "" && Edit12->Text != "") {
        a = StrToFloat(Edit9->Text);
        b = StrToFloat(Edit12->Text);
        o = 2 * (a + b);
        Edit11->Text = o;
    } else
        ShowMessage("Podaj d³ugoœci boków równoleg³oboku");
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button9Click(TObject *Sender) {
    float a, b, h, p;
    if (Edit13->Text != "" && Edit14->Text != "" && Edit15->Text != "") {
        a = StrToFloat(Edit13->Text);
        b = StrToFloat(Edit14->Text);
        h = StrToFloat(Edit15->Text);
        p = 0.5 * h * (a + b);
        Edit16->Text = p;
    } else
        ShowMessage("Podaj d³ugoœci podstaw i wysokoœæ trapezu");
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button10Click(TObject *Sender) {
    float a, b, l;
    if (Edit13->Text != "" && Edit14->Text != "") {
        a = StrToFloat(Edit13->Text);
        b = StrToFloat(Edit14->Text);
        l = 0.5 * (a + b);
        Edit16->Text = l;
    } else
        ShowMessage("Podaj d³ugoœci podstaw i wysokoœæ trapezu");

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button11Click(TObject *Sender) {
    float r, p;
    if (Edit17->Text != "") {
        r = StrToFloat(Edit17->Text);
        p = M_PI * r * r;
        Edit18->Text = p;
    } else
        ShowMessage("Podaj promieñ okrêgu/ko³a");


}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button12Click(TObject *Sender) {
    float r, l;
    if (Edit17->Text != "") {
        r = StrToFloat(Edit17->Text);
        l = 2 * M_PI * r;
        Edit18->Text = l;
    } else
        ShowMessage("Podaj promieñ okrêgu/ko³a");

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button13Click(TObject *Sender) {
    float a, b, h, v;
    if (Edit19->Text != "" && Edit21->Text != "" && Edit22->Text != "") {
        a = StrToFloat(Edit19->Text);
        b = StrToFloat(Edit21->Text);
        h = StrToFloat(Edit22->Text);
        v = a * b * h;
        Edit20->Text = v;
    } else
        ShowMessage("Podaj d³ugoœci boków i wysokoœæ prostopad³oœcianu");
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button14Click(TObject *Sender) {
    float a, b, h, p;
    if (Edit19->Text != "" && Edit21->Text != "" && Edit22->Text != "") {
        a = StrToFloat(Edit19->Text);
        b = StrToFloat(Edit21->Text);
        h = StrToFloat(Edit22->Text);
        p = a * b + 2 * a * h + 2 * b * h;
        Edit20->Text = p;
    } else
        ShowMessage("Podaj d³ugoœci boków i wysokoœæ prostopad³oœcianu");

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button15Click(TObject *Sender) {
    float r, h, v;
    if (Edit23->Text != "" && Edit24->Text != "") {
        r = StrToFloat(Edit23->Text);
        h = StrToFloat(Edit24->Text);
        v = M_PI * r * r * h;
        Edit25->Text = v;
    } else
        ShowMessage("Podaj promieñ podstawy i wysokoœæ walca");
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button16Click(TObject *Sender) {
    float r, h, p;
    if (Edit23->Text != "" && Edit24->Text != "") {
        r = StrToFloat(Edit23->Text);
        h = StrToFloat(Edit24->Text);
        p = 2 * M_PI * r * r + 2 * M_PI * r * h;
        Edit25->Text = p;
    } else
        ShowMessage("Podaj promieñ podstawy i wysokoœæ walca");
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button17Click(TObject *Sender) {
    float r, h, v;
    if (Edit26->Text != "" && Edit28->Text != "") {
        r = StrToFloat(Edit26->Text);
        h = StrToFloat(Edit28->Text);
        v = (M_PI * r * r * h) / 3;
        Edit29->Text = v;
    } else
        ShowMessage("Podaj promieñ podstawy i wysokoœæ sto¿ka");

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button18Click(TObject *Sender) {
    float r, l, p;
    if (Edit26->Text != "" && Edit27->Text != "") {
        r = StrToFloat(Edit26->Text);
        l = StrToFloat(Edit27->Text);
        p = M_PI * r * r + M_PI * r * l;
        Edit29->Text = p;
    } else
        ShowMessage("Podaj promieñ podstawy, tworz¹c¹ i wysokoœæ sto¿ka");
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button19Click(TObject *Sender) {
    float r, l, p;
    if (Edit26->Text != "" && Edit27->Text != "") {
        r = StrToFloat(Edit26->Text);
        l = StrToFloat(Edit27->Text);
        p = M_PI * r * l;
        Edit29->Text = p;
    } else
        ShowMessage("Podaj promieñ podstawy, tworz¹c¹ i wysokoœæ sto¿ka");
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button20Click(TObject *Sender) {
    float r, v;
    if (Edit30->Text != "") {
        r = StrToFloat(Edit30->Text);
        v = (4 * M_PI * r * r * r) / 3;
        Edit31->Text = v;
    } else
        ShowMessage("Podaj promieñ kuli");

}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button21Click(TObject *Sender) {
    float r, p;
    if (Edit30->Text != "") {
        r = StrToFloat(Edit30->Text);
        p = 4 * M_PI * r * r;
        Edit31->Text = p;
    } else
        ShowMessage("Podaj promieñ kuli");

}
//---------------------------------------------------------------------------




