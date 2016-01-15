Don't forget to put '*', sign of multiplication on maxima.

poly : -10*x^3*y^4*z^7+7*x^3*y^8*z^9-7*x^3*y^5*z^4-10*x^2*y^2*z^5+6*x^4*y^4*z^3+6*x^4*y^3*z^3+y^4*z+2*z^5+3*x*y^2*z-7*y^2*z;

spoly:x+2*z^2+3*y*z+4*x*z+5*y^2+6*x*y+7*x^2+8*x*z^2+9*y^2*z+10*x*y*z+11*x*y^2+12*x^3+13*y^2*z^2;

grevlexOrdering(poly,[x,y,z]);
=> 7*x^3*y^8*z^9-10*x^3*y^4*z^7-7*x^3*y^5*z^4+6*x^4*y^4*z^3+6*x^4*y^3*z^3-10*x^2*y^2*z^5+y^4*z+2*z^5+3*x*y^2*z-7*y^2*z

grevlexOrdering(poly,[z,x,y]);
=> 7*x^3*y^8*z^9-10*x^3*y^4*z^7-7*x^3*y^5*z^4+6*x^4*y^4*z^3+6*x^4*y^3*z^3-10*x^2*y^2*z^5+2*z^5+y^4*z+3*x*y^2*z-7*y^2*z

lexOrdering(poly,[x,y,z]);
=> 6*x^4*y^4*z^3+6*x^4*y^3*z^3+7*x^3*y^8*z^9-7*x^3*y^5*z^4-10*x^3*y^4*z^7-10*x^2*y^2*z^5+3*x*y^2*z+y^4*z-7*y^2*z+2*z^5

invlexOrdering(poly,[x,y,z]);
=> 7*x^3*y^8*z^9-10*x^3*y^4*z^7-10*x^2*y^2*z^5+2*z^5-7*x^3*y^5*z^4+6*x^4*y^4*z^3+6*x^4*y^3*z^3+y^4*z+3*x*y^2*z-7*y^2*z

neglexOrdering(spoly,[x,y,z]);
=> 2*z^2+3*y*z+5*y^2+9*y^2*z+13*y^2*z^2+x+4*x*z+8*x*z^2+6*x*y+10*x*y*z+11*x*y^2+7*x^2+12*x^3

revlexOrdering(poly,[x,y,z]);
=> -7*y^2*z+3*x*y^2*z+y^4*z+6*x^4*y^3*z^3+6*x^4*y^4*z^3-7*x^3*y^5*z^4+2*z^5-10*x^2*y^2*z^5-10*x^3*y^4*z^7+7*x^3*y^8*z^9

deglexOrdering(spoly,[x,y,z]);
=> 13*y^2*z^2+12*x^3+11*x*y^2+10*x*y*z+8*x*z^2+9*y^2*z+7*x^2+6*x*y+4*x*z+5*y^2+3*y*z+2*z^2+x

grevlexOrdering(spoly,[x,y,z]);
=> 13*y^2*z^2+12*x^3+11*x*y^2+10*x*y*z+9*y^2*z+8*x*z^2+7*x^2+6*x*y+5*y^2+4*x*z+3*y*z+2*z^2+x
