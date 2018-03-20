# xiaoyi
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Windows.Forms;

namespace WindowsFormsApplication1
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }
        private void button1_Click(object sender, EventArgs e)
        {
            string name = "xiaoyi"; 
            string password = "123"; 

            if (string.Equals(textBox1.Text, name) && string.Equals(textBox2.Text, password))
                MessageBox.Show("登录成功！");
            else
                MessageBox.Show("登陆失败！");
        }

        private void label1_Click(object sender, EventArgs e)
        {

        }
    }

}
