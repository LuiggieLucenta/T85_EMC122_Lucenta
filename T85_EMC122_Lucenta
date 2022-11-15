#include <iostream>
#include <glut.h>

using namespace std;

void display();
void reshape(int,int);
void update(int);

float angle = 0; //rotation angle


void init()
{
	
	glClearColor(1.0,0.0f,0.0f,1.0f); //set background to black
	
}

int main(int argc,char**argv)
{
	glutInit(&argc,argv);
	glutInitDisplayMode(GLUT_RGB | GLUT_DOUBLE); //display modes
	
	glutInitWindowPosition(200,100); //window postion
	glutInitWindowSize(500,500); //window size
	glutCreateWindow ("Lucenta_M1A2"); //create the initialized window with name
	
	glutDisplayFunc(display); //initialize display function
	glutReshapeFunc(reshape); //initialize reshape function
	
	init();

	glutTimerFunc(1000/60,update,0); //add timer

	glutMainLoop();//loop at the functions

}

void display()
{
	
	glClear(GL_COLOR_BUFFER_BIT);//clear color
	
	glLoadIdentity();//clear transforms

	
	glPushMatrix();
	glColor3f(0.0f, 0.0f, 0.0f);
	glLineWidth(20.0f);


	glBegin(GL_LINE_LOOP);	
		glVertex2f(-6.5f, -6.0f);
		glVertex2f(-6.5f, -7.5f);
		glVertex2f(-4.0f, -5.5f);
		glVertex2f(-5.5f, -5.0f);
		glVertex2f(-2.5f, -3.5f);
		glVertex2f(-4.0f, -5.0f);
		glVertex2f(-3.0f, -5.5f);
		glVertex2f(-5.0f, -7.5f);
		glVertex2f(0.0f, -9.5f);
		glVertex2f(5.0f, -7.5f);
		glVertex2f(3.0f, -5.5f);
		glVertex2f(4.0f, -5.0f);
		glVertex2f(2.5f, -3.5f);
		glVertex2f(5.5f, -5.0f);
		glVertex2f(4.0f, -5.5f);
		glVertex2f(6.5f, -7.5f);
		glVertex2f(6.5f, -6.0f);
		glVertex2f(8.5f, 0.0f);
		glVertex2f(6.5f, 4.0f);
		glVertex2f(6.5f, 5.5f);
		glVertex2f(4.5f, 3.5f);
		glVertex2f(5.5f, 3.0f);
		glVertex2f(2.5f, 1.5f);
		glVertex2f(4.0f, 3.0f);
		glVertex2f(3.0f, 3.5f);
		glVertex2f(5.0f, 5.5f);
		glVertex2f(0.0f, 7.5f);
		glVertex2f(-5.0f, 5.5f);
		glVertex2f(-3.0f, 3.5f);
		glVertex2f(-4.0f, 3.0f);
		glVertex2f(-2.5f, 1.5f);
		glVertex2f(-5.5f, 3.0f);
		glVertex2f(-4.5f, 3.5f);
		glVertex2f(-6.5f, 5.5f);
		glVertex2f(-6.5f, 4.0f);
		glVertex2f(-8.5f, 0.0f);
	glEnd();
	glPopMatrix();
	
	
	glPushMatrix();
	glColor4ub(180.0f, 127.0f, 57.0f, 0); 
	
	glBegin(GL_POLYGON);
		glVertex2f(-6.5f, -6.0f);
		glVertex2f(-6.5f, -7.5f);
		glVertex2f(-4.0f, -5.5f);
		glVertex2f(-5.5f, -5.0f);
		glVertex2f(-2.5f, -3.5f);
		glVertex2f(-2.5f, 0.0f);
		glVertex2f(-8.5f, 0.0f);
	glEnd(); 

	glBegin(GL_POLYGON);
		glVertex2f(-8.5f, 0.0f);
		glVertex2f(-2.5f, 0.0f);
		glVertex2f(-2.5f, 1.5f);
		glVertex2f(-5.5f, 3.0f);
		glVertex2f(-6.5f, 4.0f);
	glEnd(); 
	
	glBegin(GL_QUADS);
		glVertex2f(-6.5f, 4.0f);
		glVertex2f(-5.5f, 3.0f);
		glVertex2f(-4.5f, 3.5f);
		glVertex2f(-6.5f, 5.5f);
	glEnd(); 

	glBegin(GL_POLYGON);
		glVertex2f(-5.5f, -7.5f);
		glVertex2f(0.0f, -9.5f);
		glVertex2f(5.0f, -7.5f);
		glVertex2f(3.0f, -5.5f);
		glVertex2f(-3.0f, -5.5f);
	glEnd(); 

	glBegin(GL_POLYGON);
		glVertex2f(-4.0f, -5.0f);
		glVertex2f(-3.0f, -5.5f);
		glVertex2f(3.0f, -5.5f);
		glVertex2f(4.0f, -5.0f);
		glVertex2f(2.5f, -3.5f);
		glVertex2f(-2.5f, -3.5f);
	glEnd(); 

	glBegin(GL_QUADS);
		glVertex2f(4.0f, -5.5f);
		glVertex2f(6.5f, -7.5f);
		glVertex2f(6.5f, -6.0f);
		glVertex2f(5.5f, -5.0f);
	glEnd(); 

	glBegin(GL_POLYGON);
		glVertex2f(2.5f, -3.5f);
		glVertex2f(5.5f, -5.0f);
		glVertex2f(6.5f, -6.0f);
		glVertex2f(8.5f, 0.0f);
		glVertex2f(6.5f, 4.0f);
		glVertex2f(5.5f, 3.0f);
		glVertex2f(2.5f, 1.5f);
	glEnd(); 

	glBegin(GL_QUADS);
		glVertex2f(5.5f, 3.0f);
		glVertex2f(6.5f, 4.0f);
		glVertex2f(6.5f, 5.5f);
		glVertex2f(4.5f, 3.5f);		
	glEnd(); 

	glBegin(GL_POLYGON);
		glVertex2f(-2.5f, 1.5f);
		glVertex2f(2.5f, 1.5f);
		glVertex2f(4.0f, 3.0f);
		glVertex2f(3.0f, 3.5f);
		glVertex2f(-3.0f, 3.5f);
		glVertex2f(-4.0f, 3.0f);
	glEnd(); 

	glBegin(GL_POLYGON);
		glVertex2f(-3.0f, 3.5f);
		glVertex2f(3.0f, 3.5f);
		glVertex2f(5.0f, 5.5f);
		glVertex2f(0.0f, 7.5f);
		glVertex2f(-5.0f, 5.5f);
	glEnd(); 

	glBegin(GL_QUADS);
		glVertex2f(-2.5f, -3.5f);
		glVertex2f(2.5f, -3.5f);
		glVertex2f(2.5f, 1.5f);
		glVertex2f(-2.5f, 1.5f);
	glEnd(); 

	

	


	glutSwapBuffers(); //Send the scene to the screen
}

void reshape(int w, int h)
{
	glViewport(0,0,(GLsizei)w, (GLsizei)h);
	glMatrixMode(GL_PROJECTION);
	gluOrtho2D(-10,10,-10,10);//size of the world
	glMatrixMode(GL_MODELVIEW);
}

void update(int)
{


	//looping animation logic
	angle+=0.8;
	if(angle>360.0f)
		angle=angle-360.0f;

	glutPostRedisplay();
	glutTimerFunc(1000/60,update,0);

}
