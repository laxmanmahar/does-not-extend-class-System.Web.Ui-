# does-not-extend-class-System.Web.Ui-
Parser Error Message: 'Ecommerce.ForgotPassword' is not allowed here because it does not extend class 'System.Web.UI.Page'.


Line 1: 
ERROR:<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="ForgotPassword.aspx.cs" Inherits="Ecommerce.ForgotPassword" %>
Line 2:  
Line 3: 


Correct the namespace
<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="ForgotPassword.aspx.cs" Inherits="ForgotPassword" %>
