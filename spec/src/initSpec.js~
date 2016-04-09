

import init from '../../src/init';

describe('The Init Functionality', () => {
  it('should be defined as a function', () => {
    expect(init).toEqual(jasmine.any(Function));	  
  });

  it('should iterate through SOURCE_IMPORTS', () => {
    spyOn(Array.prototype, 'map');
    init();
    expect(Array.prototype.map).toHaveBeenCalled();   
  });
});
